# 20180926

import java.awt.*;
import java.awt.event.*;
import javax.swing.*;
public class Main {

    /**
     * @param args
     */
    public static void main(String[] args) {
        // TODO Auto-generated method stub
        MainFrame mFrm = new MainFrame();
        mFrm.setVisible(true);
    }

}
class MainFrame extends Frame {
    private String str = new String();
    private JButton btn1 = new JButton("0");
    private JButton btn2 = new JButton("1");
    private JButton btn3 = new JButton("2");
    private JButton btn4 = new JButton("3");
    private JButton btn5 = new JButton("4");
    private JButton btn6 = new JButton("5");
    private JButton btn7 = new JButton("6");
    private JButton btn8 = new JButton("7");
    private JButton btn9 = new JButton("8");
    private JButton btn10 = new JButton("9");
    private JButton btnsub = new JButton("Submit");
    private JButton btnexit = new JButton("Exit");
    private JPasswordField   txtf = new JPasswordField(str);

    public MainFrame(){
        initcomp();
    }
    private void initcomp() {
        this.setLayout(null);
        this.setLocation(250, 135);
        this.setSize(430, 300);
        this.addWindowListener(new WindowAdapter() {
            public void windowClosing(WindowEvent we) {
                System.exit(0);
            }
        });
        this.add(btn1);
        this.add(btn2);
        this.add(btn3);
        this.add(btn4);
        this.add(btn5);
        this.add(btn6);
        this.add(btn7);
        this.add(btn8);
        this.add(btn9);
        this.add(btn10);
        this.add(btnsub);
        this.add(btnexit);
        this.add(txtf);
        txtf.setBounds(20,50,390,30);
        btn1.setBounds(20,100,90,50);
        btn2.setBounds(120,100,90,50);
        btn3.setBounds(220,100,90,50);
        btn4.setBounds(320,100,90,50);
        btn5.setBounds(20,160,90,50);
        btn6.setBounds(120,160,90,50);
        btn7.setBounds(220,160,90,50);
        btn8.setBounds(320,160,90,50);
        btn9.setBounds(20,220,90,50);
        btn10.setBounds(120,220,90,50);
        btnsub.setBounds(220,220,90,50);
        btnexit.setBounds(320,220,90,50);

        btn1.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"0";
                txtf.setText(str);
            }
        });
        btn2.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"1";
                txtf.setText(str);
            }
        });
        btn3.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"2";
                txtf.setText(str);
            }
        });
        btn4.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"3";
                txtf.setText(str);
            }
        });
        btn5.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"4";
                txtf.setText(str);
            }
        });
        btn6.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"5";
                txtf.setText(str);
            }
        });
        btn7.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"6";
                txtf.setText(str);
            }
        });
        btn8.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"7";
                txtf.setText(str);
            }
        });
        btn9.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"8";
                txtf.setText(str);
            }
        });
        btn10.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                str=str+"9";
                txtf.setText(str);
            }
        });
        btnexit.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // TODO Auto-generated method stub
                System.exit(0);
            }
        });
    }

}
