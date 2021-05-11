import javax.swing.*;

public class swing extends JFrame   {
     JLabel l1,l2,l3,l4;
     JTextField t1,t2;
     JButton b1;

 public swing (){

 }
 public swing (String s){
     super(s);
    }

    public void setcomponents(){
      l1=new JLabel("select item");
      l1.setBounds(50,40,300,20);
      l2=new JLabel("first item");
	  l2.setBounds(50,80,120,20);
      l3=new JLabel("second item");
	  l3.setBounds(50,100,120,20);
      l4=new JLabel("total item");
	  l4.setBounds(80,140,100,20);
      t2=new JTextField();
	  t2.setBounds(80,100,100,20);
      t1=new JTextField();
	  t1.setBounds(80,80,100,20);
      b1=new JButton("ADD");
      b1.setBounds(100,160,100,20);
      setLayout(null);
      add(l1);
      add(l2);
      add(l3);
      add(l4);
      add(t1);
      add(t2);
      add(b1);
      
 }
    public static void main(String[] args){

        swing x=new swing("window");
        x.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        x.setcomponents();
        x.setVisible(true);
        x.setSize(300,300);

    }

}
