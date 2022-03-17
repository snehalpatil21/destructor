# destructor
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace destructor
{
    class using System Program
    {
            public int age;
            public string name;
            Program (int age1,string name1)
            {
                age=age1;
                name=name1;
            }
          int age2()
          {
              return age;
          }
          string name2()
          {
              return name;
          }
          ~Program()
          {
              Console.WriteLine("destructor called");
          }
           public static void Main(String[] args)
           {
               Program p=new Program(89,"snehal");
               Console.WriteLine(p.age2());
               Console.WriteLine(p.name2());
               //Console.ReadLine();
           }
        }
    }
