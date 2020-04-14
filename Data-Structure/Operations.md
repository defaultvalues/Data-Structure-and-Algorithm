# Operations in C++

## Vector

```C++
# include<vector>
# include<iostream>
using namespace std;

int main()
{
	vector<int> obj;
	for(int i=0;i<10;i++) // push_back(elem)在数组最后添加数据 
	{
		obj.push_back(i);
	}
	for(int i=0;i<5;i++) // 去掉数组最后一个数据 
	{
		obj.pop_back();
	}
	obj.erase(obj.begin()+1,obj.begin()+3);//删除a中第1个（从第0个算起）到第2个元素
	cout<<obj.size(); // size of vector
	obj.clear(); // 清除容器中所有数据
	return 0;
}

```
## Stack

```c++
# include<stack>
using namespace std;



```
