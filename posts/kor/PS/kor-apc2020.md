# Alsing Programming Contest 2020

| 문제| 시간 제한 | 메모리 제한 |
|:-:|:-:|:-:|
|[A](#A)|2초|1024 MB|
|[B](#B)|2초|1024 MB|

<div class="divider"></div>

## A - Number of Multiples <a id="A"></a>
```cpp
int main(){
  ios; cfs(15);
  int cnt=0;
  INT(l,r,d);
  rep2(i,l,r+1) {
    if(i%d==0) ++cnt;
  }
  cout<<cnt<<endl;
  ret;
}
```

## B - An Odd Problem <a id="B"></a>
```cpp
int main(){
  ios; cfs(15);
  int cnt = 0;
  INT(n);
  rep(i,n) {
    int a;
    cin>>a;
    if((i+1)&1 && (a&1)) ++cnt;
  }
  cout<<cnt<<endl;
  ret;
}
```
