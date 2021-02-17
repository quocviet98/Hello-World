# Hello-World
this is first project
#include iostream

using namespace std;

int main{
  int n;
  int s;
  cout<<"printf a number: ";
  cin>>n;
  for(int i = 1; i<=n; i++){
    s = i + s;
  }
  cout<<"sum = "<<s;
  system("pause");
  return 0;
}
