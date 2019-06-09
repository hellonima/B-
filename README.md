# B-
#include <iostream>
#include <string>

#define maxn 500 
using namespace std;

int tempNum[maxn] = {0};
string num;

int main(int argc, char** argv) {
	int memset;
	while(cin)
	{
		int len = num.size();
		
		memset(tempNum,0,sizeof(tempNum));
		int j = 0;
		while(len >= 0){
			tempNum[j++] = (num[len] - '0')*;
		}
		for(int index = 0; index < j; index++){
			if(tempNum[index] >= 10){
				tempNum[index] = tempNum[index] % 10;
				tempNum[index + 1] += 1;
			}
		} 
		int index;
		num;
		if(tempNum[j] == 0)
			index = j - 1;
		else 
			index = j;
		for(index; index >= 0; index--) {
			num+=(tempNum[index] + '0');
		}
		cout;
	}
	return 0;
}
