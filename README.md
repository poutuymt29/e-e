# e-e

int usc(int a, int b)
{
	int r = a % b;
	while (r)
	{
		a = b;
		b = r;
		r = a % b;
	}

	return b;
}

class phanso
{
	public:
		int tuso, mauso;
	void nhap()
	{
		cout << "Nhap tu so : ";
		cin >> tuso;
		cout << "Nhap mau so : ";
		cin >> mauso;
	}
