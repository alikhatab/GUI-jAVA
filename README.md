# GUI-jAVA 
It is a program in jAVA which is saying one sentecne 


import java.awt.FlowLayout; // 

import javax.swing.JFrame; // basic window

import javax.swing.JLabel; // text and imagin






        

public class GU2 extends JFrame {

    
        private JLabel item1;
        
        public GU2 () { // constructor that make the layout. 
            super ("the title bar"); // this add the title 
            
            setLayout (new FlowLayout ()); // this give us defult layout. 
            
            item1 = new JLabel ("this is a sentenece");
            
            item1.setToolTipText("this is gona show in hover");
            
            add (item1);
            
            
        }
        
    }
    
/*}*/
