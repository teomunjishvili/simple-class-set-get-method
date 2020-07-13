#include<iostream>
#include<string>
using namespace std;

class Student
{
    /*private variables: */
        string firstname;
        string lastname;
        int age;
    
    public:
        void setFirstname (string x)
        {
            firstname=x;
        }
        
        void setLastname (string x)
        {
           lastname=x;
        }
        
        void setAge (int x)
        {
            age=x;
        }
        
        string getFirstname ()
        {
            return firstname;
        }
        
        string getLastname ()
        {
            return lastname;
        }
        
        int getAge ()
        {
            return age;
        }
};

int main()
{
    Student stud;
    
    stud.setFirstname("Teo");
    cout<<stud.getFirstname()<<endl;
    
    stud.setLastname("Munjishvili");
    cout<<stud.getLastname()<<endl;
    
    stud.setAge(20);
    cout<<stud.getAge()<<endl;
    
    return 0;
}
