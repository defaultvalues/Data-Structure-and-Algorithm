# Operations in C++

## Vector

```C++
# include<vector>
using namespace std;

int main()
{
   vector<int> obj;
   for(int i=0;i<10;i++) // push_back(elem)在数组最后添加数据 
   {
       obj.push_back(i);
   }
   int l=obj.size(); // size of vector
   for(int i=0;i<5;i++) // 去掉数组最后一个数据 
    {
        obj.pop_back();
    }
   obj.clear(); // 清除容器中所有数据
    
 
   return 0;
}

```
## Stack

```c++
# include<stack>
using namespace std;



```
