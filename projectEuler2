#include  <iostream>

using namespace std;

int main()
{
	int evenSum = 2;
	int prev1 = 2, prev2 = 1;
	int n, temp;
	cin >> n;

	do
	{
		if (n == 1)
			evenSum = 0;
		else if (n == 2)
			evenSum = 2;
		else
		{

			if ((prev1 + prev2) % 2 == 0)
			{
				evenSum += (prev1 + prev2);
			}
			temp = prev1;
			prev1 = prev1 + prev2;
			prev2 = temp;
		}
	} while (prev2 + prev1 <= n);
	cout << evenSum;
	return 0;
}
