# vehicle-Parking-management-system
#include<iostream>
using namespace std;
int main()
{
	int u_input; int amount = 0,count = 0;
	int car=0,riksha=0,motercycle=0;
	// menu
while(true){
	cout<<"\n\n Welcome To Parking System!!\n"<<endl;;
	cout<<"MADE BY:"<<endl;
			cout<<"******************"<<endl;
	cout<<" Peer Adnan Safder Shah.\n Roll no. 68\n\n";
	cout<<" Sahil Hussain Pandit.\n Roll no. 70\n\n";
	cout<<" Mohd Altaf Najar.\n Roll no. 71\n";
		cout<<"******************"<<endl<<endl;
	
		cout<<"******************"<<endl;
	cout<<"TwoWheeler parking charges\t=50"<<endl;
	cout<<"ThreeWheeler parking charges\t=100"<<endl;
	cout<<"fourWheeler parking charges\t=200"<<endl;
	cout<<"******************"<<endl;
	
	cout<<"\t\tPress 1 for motercycle"<<endl;
	cout<<"\t\tPress 2 for Car"<<endl;
	cout<<"\t\tPress 3 for riksha"<<endl;
	cout<<"\t\tPress 4 for Show Record"<<endl;
	cout<<"\t\tPress 5 for Delete Record"<<endl;
	
	cin>>u_input;
	 if(u_input==1)
	{
		if(count<=50){
		
		amount = amount + 50 ;
		count = count + 1;
		motercycle=motercycle+1;
	}
	else
	cout<<"No More parking!<<endl";
}
	else if(u_input==2)
	{
		if(count<=50){
		amount = amount + 100 ;
		count = count + 1;
		car = car+1;
	}
	else
	cout<<"No more parking!<<endl";
	}
	else if(u_input==3)
	{
		if(count<=50){
		amount = amount + 200 ;
		count = count + 1;
		riksha=riksha+1; 
		}
		else
		cout<<"No more parking !"<<endl;
	}
	else if(u_input==4)
	{
		cout<<"*************"<<endl;
			cout<<"*************"<<endl;
		cout<<"The total amount = "<<amount<<endl;
		cout<<"The total number of Vehicals Parked = "<<count<<endl;
	    cout<<"The total number of Cars = "<<car<<endl;
		cout<<"The total number of Rikshas = "<<riksha<<endl;
		cout<<"The total number of Motercycle = "<<motercycle<<endl;
			cout<<"*************"<<"\t\tTHIS IS OUR MINI  PROJECT IN C++"<<endl;
				cout<<"*************"<<endl;
	}
	else if(u_input==5)
	{
		cout<<"*************"<<endl;
			cout<<"*************"<<endl;
		amount = 0 ;
		count = 0 ;
		car=0;
		riksha=0;
	motercycle=0;
		cout<<"*************"<<endl;
			cout<<"*************"<<endl;
		cout<<"Record Deleated"<<endl;
		cout<<"*************"<<endl;
			cout<<"*************"<<endl;
	}
	else{
       cout<<"Invalid input!!"<<endl;
   }
}
	return 0;
}
