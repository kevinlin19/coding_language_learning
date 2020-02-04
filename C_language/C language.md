---
tags: codeing language learning
---

# C language
# IDE
- Code Blocks

# 執行
```cpp=
int main()
{
    printf('abc');
    
    return 0;
}
```

# 變數設定
變數種類可分為:
- int
- double/float
- char
 
字串變數一定要有中括號[ ]，而且用雙引號""，單一字元**不用中括號**且使用**單引號''**
可以從中改變變數，不用在宣告。
```cpp=
int main()
{
    char myFirstVar[] = 'Kevin';
    char firstLetter = 'K';
    int myFirstAge = 27;
    
    printf(myFirstAge);
    
    myFirstAge = 100;
    printf(myFirstAge);
    
    return 0;
}
```

# Print
- %s, 放入char變數， 括號內要加入逗號
- %c, 單一字元
- %d/%f, 放入number變數
```cpp=
printf("    /|");
printf("   / |");
printf("  /  |");
printf(" /   |");
printf("/____|");

printf("My name is %s/n", charVar);
printf("I am %d years old./n", intVar);


```

# 運算


整數運算整數回
浮點數運算浮點數回
浮點數與整數運算浮點數回

---
運算函數:
pow() 指數
sqrt() 根號
ceil() 無條件進位
floor() 無條件捨去

```cpp=
printf("%d", 5 / 4) //1
printf("%f", 5 / 4.0) //1.25
```

