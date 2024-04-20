

#include <iostream>
#include <vector>
#include <string>
using namespace  std ;

int main (){
//whale game starts here 
string input = "turpentine and turtle ";

vector <char> vowel = {'a','e','i','o','u'};

vector <char> result ={} ;

//processing the whale game for humen language 

for (int i ; i<input.size();i++){
 for (int j=0;j<vowel.size();j++){
  if (input[i]== vowel [j]){
    result.push_back(input[i]);
  
  if (input [i]=='u'||input [i]=='e'){
    result.push_back(input [i]);
  }
  }
 } 
}

for (int k=0 ; k<result.size();k++){
  cout << result [k];
}

return  0;
}
