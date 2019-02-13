using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace 계산기
{
    public partial class main_Form : Form
    {
        int index1 = 0, index2 = 0;
        int op = 0;
        int A = 0, B = 0, C = 0;

        string Data;


        public main_Form()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("1");
            if (op > 0) index2++;
            else index1++;
        }

        private void button2_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("2");
            if (op > 0) index2++;
            else index1++;
        }

        private void button3_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("3");
            if (op > 0) index2++;
            else index1++;
        }

        private void button4_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("4");
            if (op > 0) index2++;
            else index1++;
        }

        private void button5_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("5");
            if (op > 0) index2++;
            else index1++;
        }

        private void button6_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("6");
            if (op > 0) index2++;
            else index1++;
        }

        private void button7_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("7");
            if (op > 0) index2++;
            else index1++;
        }

        private void button8_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("8");
            if (op > 0) index2++;
            else index1++;
        }

        private void button9_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("9");
            if (op > 0) index2++;
            else index1++;
        }

        private void button10_Click(object sender, EventArgs e)
        {
            textBox1.AppendText("0");
            if (op > 0) index2++;
            else index1++;
        }

        private void button11_Click(object sender, EventArgs e)
        {
            while (op < 1)
            {
                textBox1.AppendText("+");
                op++;
            }

        }

        private void button12_Click(object sender, EventArgs e)
        {
            while (op < 1)
            {
                textBox1.AppendText("-");
                op+=2;
            }
        }

        private void button13_Click(object sender, EventArgs e)
        {
            while (op < 1)
            {
                textBox1.AppendText("*");
                op+=3;
            }
        }

        private void button16_Click(object sender, EventArgs e)
        {
            while (op < 1)
            {
                textBox1.AppendText("/");
                op+=4;
            }
        }

        private void button14_Click(object sender, EventArgs e)
        {
 /*           while (index < 1)
                return;
            textBox1.Select(--index, 1);
            textBox1.Cut();
   */     }

        private void button15_Click(object sender, EventArgs e)
        {
            Data = textBox1.Text;
            for(int i=0; i < index1; i++)
              {
                  A += (Data[i] - 48) * Convert.ToInt32(Math.Pow(10 , (index1 - i)) / 10); //Data && Math.Pow 형변환 버그
              }
            
            for(int i=0; i < index2; i++)
              {
                  B += (Data[index1+i+1] - 48) * Convert.ToInt32(Math.Pow(10 , (index1 - i)) / 100); //Data && Math.Pow 형변환 버그
              }
            

            switch (op)
            {
                case 1:
                    C = A + B;
                    break; //덧셈
                case 2:
                    C = A - B;
                    break; //뺄셈
                case 3:
                    C = A * B;
                    break; //곱셈
                case 4:
                    C = A / B;
                    break; //나눗셈
            }

            textBox2.AppendText(C.ToString());


 //           index++;
        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }

    }
}
