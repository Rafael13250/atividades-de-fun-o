# atividades-de-fun-o
1)
   #include <iostream>

using namespace std;
int maior(int n)
{
	   if(n>0){
		   return 1;
	   }
	   if(n<0){
		   return -1;
	   }else{
		   return 0;
	   }
	   	
}
int main()
{
	int n;
	cin>>n;
	int e = maior(n);
	cout<<e;
	
   
    return 0;       
}

2)#include <iostream>

using namespace std;
int maior(int n, int e)
{
	if(e>n){
		return e;
	}else{
		return n;
	}
}
int main()
{
    int n , e;
    cin>>n>>e;
    int r = maior(n,e);
    cout<<r;
    return 0;       
}

3)#include <iostream>

using namespace std;
int dobro (int n)
{
	return 2*n;
}
int main()
{
    int n;
    cin>>n;
    int r = dobro(n);
    cout<<r;
    return 0;       
}

4)#include <iostream>

using namespace std;

float volume(int R)
{
    return 4.0 / 3.0 * 3.14 * (R * R * R);
}

int main()
{
    int R;
    cin >> R;
    float e = volume(R);
    cout << e;
    return 0;
}

5)#include <iostream>

using namespace std;
int Fahrenheit(int C)
{
	return C * (9.0/5.0) + 32.0;
}
int main()
{
	int C;
	cin>>C;
    int F = Fahrenheit(C);
    cout<<F;
    return 0;       
}
