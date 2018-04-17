# count_and_say

由题意出发。定义int count来记录相等数字个数，再加入字符串即可。例如1112，为3112。

首先res='1'
while(n--)
{
  字符串cur为空，再进行for循环，循环次数为res的大小
  {
    记录相同数字个数count=1
    while，若后一个数字与当前数字相等
    {
     计数器count+1；
     i指向下一个；
    }
    cur+=count（个数）+res[i](对应数字)；
  }
}
