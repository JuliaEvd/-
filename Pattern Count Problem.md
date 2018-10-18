# Bioinformatics
#include <string>
#include <iostream>                                                                                                                                                                                          

using namespace std;


int main()
{
	string s1, s2;
	cin >> s1;
	cin >> s2;
	size_t count = 0;
	int p = 0;

	while ((p = s2.find(s1, p)) != s2.npos) {
		++count;
		++p;
	}
	cout << count << endl;
	return 0;
}
