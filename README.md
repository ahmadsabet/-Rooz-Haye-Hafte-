#include <iostream>
using namespace std;
int main()
{
    cout << "Give Arrays The Numbers:" << endl;
    
    int x[10];
    
    int *p;
    
    for(int i=0;i<10;i++){             
        cin>>x[i];
        p=&x[i];

cout<<"Awnser:"<<endl;
   
switch(*p){
    
case 0:
    
    cout<<"Shanbe";
    
    break;
    
    case 1:
    
    cout<<"Yek Shanbe";
    
    break;
    
    case 2:
    
       cout<<"Dow Shanbe";
    
             break;
    
                case 3:
    
                cout<<"Se Shanbe";
    
                break;
    
   case 4:
    cout<<"Chehar Shanbe";
    break;
    
    case 5:
    cout<<"Panj Shanbe";
    break;
    
    case 6:
       cout<<"Jomeh";
             break;
    
    default:
        cout<<"Error";
}
    
      p++;
    }
cout<<endl;

// Faghat ARIA & JIMIZ Mitonan Ski Beran .
