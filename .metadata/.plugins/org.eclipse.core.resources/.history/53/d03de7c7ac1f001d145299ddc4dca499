import java.awt.EventQueue;
import java.awt.Font;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.SwingConstants;

public class Calculator {

	private JFrame frame;
	private String func = "Add";
	private int firstNumber;
	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Calculator window = new Calculator();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public Calculator() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.getContentPane().setFont(new Font("MS UI Gothic", Font.PLAIN, 20));
		frame.setBounds(100, 100, 320, 450);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.getContentPane().setLayout(null);
		
		
		JLabel lblNewLabel = new JLabel("0");
		lblNewLabel.setHorizontalAlignment(SwingConstants.RIGHT);
		lblNewLabel.setFont(new Font("MS UI Gothic", Font.PLAIN, 50));
		lblNewLabel.setBounds(12, 10, 265, 84);
		frame.getContentPane().add(lblNewLabel);
		
		JButton btnNewButton = new JButton("7");
		btnNewButton.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
			}
		});
		btnNewButton.setBounds(12, 111, 61, 61);
		frame.getContentPane().add(btnNewButton);
		
		JButton btnNewButton_1 = new JButton("8");
		btnNewButton_1.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_1.setBounds(85, 111, 61, 61);
		frame.getContentPane().add(btnNewButton_1);
		
		JButton btnNewButton_2 = new JButton("9");
		btnNewButton_2.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_2.setBounds(158, 111, 61, 61);
		frame.getContentPane().add(btnNewButton_2);
		
		JButton btnNewButton_3 = new JButton("/");
		btnNewButton_3.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				String curr = lblNewLabel.getText();
				firstNumber = Integer.parseInt(curr);
				lblNewLabel.setText("0");
				func = "Div";
			}
		});
		btnNewButton_3.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_3.setBounds(231, 111, 61, 61);
		frame.getContentPane().add(btnNewButton_3);
		
		JButton btnNewButton_4 = new JButton("4");
		btnNewButton_4.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_4.setBounds(12, 182, 61, 61);
		frame.getContentPane().add(btnNewButton_4);
		
		JButton btnNewButton_3_1 = new JButton("X");
		btnNewButton_3_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				String curr = lblNewLabel.getText();
				firstNumber = Integer.parseInt(curr);
				lblNewLabel.setText("0");
				func = "Mult";
			}
		});
		btnNewButton_3_1.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_3_1.setBounds(231, 182, 61, 61);
		frame.getContentPane().add(btnNewButton_3_1);
		
		JButton btnNewButton_2_1 = new JButton("6");
		btnNewButton_2_1.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_2_1.setBounds(158, 182, 61, 61);
		frame.getContentPane().add(btnNewButton_2_1);
		
		JButton btnNewButton_1_1 = new JButton("5");
		btnNewButton_1_1.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_1_1.setBounds(85, 182, 61, 61);
		frame.getContentPane().add(btnNewButton_1_1);
		
		JButton btnNewButton_5 = new JButton("1");
		btnNewButton_5.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_5.setBounds(12, 253, 61, 61);
		frame.getContentPane().add(btnNewButton_5);
		
		JButton btnNewButton_3_2 = new JButton("-");
		btnNewButton_3_2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				String curr = lblNewLabel.getText();
				firstNumber = Integer.parseInt(curr);
				lblNewLabel.setText("0");
				func = "Sub";
			}
		});
		btnNewButton_3_2.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_3_2.setBounds(231, 253, 61, 61);
		frame.getContentPane().add(btnNewButton_3_2);
		
		JButton btnNewButton_2_2 = new JButton("3");
		btnNewButton_2_2.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_2_2.setBounds(158, 253, 61, 61);
		frame.getContentPane().add(btnNewButton_2_2);
		
		JButton btnNewButton_1_2 = new JButton("2");
		btnNewButton_1_2.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_1_2.setBounds(85, 253, 61, 61);
		frame.getContentPane().add(btnNewButton_1_2);
		
		JButton btnNewButton_6 = new JButton(".");
		btnNewButton_6.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_6.setBounds(12, 324, 61, 61);
		frame.getContentPane().add(btnNewButton_6);
		
		JButton btnNewButton_3_3 = new JButton("+");
		btnNewButton_3_3.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				String curr = lblNewLabel.getText();
				firstNumber = Integer.parseInt(curr);
				lblNewLabel.setText("0");
				func = "Add";
			}
		});
		btnNewButton_3_3.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_3_3.setBounds(231, 324, 61, 61);
		frame.getContentPane().add(btnNewButton_3_3);
		
		JButton btnNewButton_2_3 = new JButton("=");
		btnNewButton_2_3.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				switch(func) {
					case "Add":{
						int currValue = Integer.parseInt(lblNewLabel.getText()); 
						lblNewLabel.setText((firstNumber + currValue)+"");
						break;
					}
					case "Sub":{
						int currValue = Integer.parseInt(lblNewLabel.getText()); 
						lblNewLabel.setText((firstNumber - currValue)+"");
						break;
					}
					case "Mult":{
						int currValue = Integer.parseInt(lblNewLabel.getText()); 
						lblNewLabel.setText((firstNumber * currValue)+"");
						break;
					}
					case "Div":{
						int currValue = Integer.parseInt(lblNewLabel.getText()); 
						lblNewLabel.setText((firstNumber / currValue)+"");
						break;
					}
				}
			}
		});
		btnNewButton_2_3.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_2_3.setBounds(158, 324, 61, 61);
		frame.getContentPane().add(btnNewButton_2_3);
		
		JButton btnNewButton_1_3 = new JButton("0");
		btnNewButton_1_3.addActionListener(new NumberActionListner(lblNewLabel,"0"));
		btnNewButton_1_3.setFont(new Font("MS UI Gothic", Font.BOLD, 25));
		btnNewButton_1_3.setBounds(85, 324, 61, 61);
		frame.getContentPane().add(btnNewButton_1_3);
		
		btnNewButton_5.addActionListener(new NumberActionListner(lblNewLabel,"1"));
		btnNewButton_1_2.addActionListener(new NumberActionListner(lblNewLabel,"2"));
		btnNewButton_2_2.addActionListener(new NumberActionListner(lblNewLabel,"3"));
		btnNewButton_4.addActionListener(new NumberActionListner(lblNewLabel,"4"));
		btnNewButton_1_1.addActionListener(new NumberActionListner(lblNewLabel,"5"));
		btnNewButton_2_1.addActionListener(new NumberActionListner(lblNewLabel,"6"));
		btnNewButton.addActionListener(new NumberActionListner(lblNewLabel,"7"));
		btnNewButton_1.addActionListener(new NumberActionListner(lblNewLabel,"8"));
		btnNewButton_2.addActionListener(new NumberActionListner(lblNewLabel,"9"));
		btnNewButton_6.addActionListener(new NumberActionListner(lblNewLabel,"."));
	}
}

class NumberActionListner implements ActionListener{

	private JLabel label;
	private String text;
	
	public NumberActionListner(JLabel l, String s) {
		label = l;
		text = s;
	}
	public void actionPerformed(ActionEvent e) {
		String curr = label.getText();
		if(curr.equals("0")) {
			label.setText(text);
		}else {
			label.setText(label.getText()+text);
		}
	}
	
}

