### 8.이미지 넣기
[PCWK](https://cafe.daum.net/pcwk)
![여름](https://github.com/ODH125/markdown20230717/blob/main/abc.jpeg)

### 6. 가로선
화면 전체를 가로지르는 가로선: -,* 을 3개이상

### 5.목록
#### 하위 목록
1.  아이템1
2.  아이템2

#### 무순서 목록
* 목록이름
- 목록이름
+ 목록이름

#### 순서 목록
1. 목록이름
2. 목록이름
3. 목록이름

### 4.코드 블록
```python
def main():
    total = 0
    count = int(input("구매수를 입력하세요"))
    for i in range(1,count+1):
        price = 1000
        print("2+1상품입니다")

        if (i % 3 ==0):
            pass
        else:
            total = total + price
    print("총금액은 {0}입니다".format(total))
main()
```

### 3.인용상자
> 여기에 인용할내용을 넣으면 됩니다.
> 빈줄이 없으면 자동으로 인용상자에 포함 됩니다.
식사 맛나게 하셨나요.

인용이 끝났습니다.

### 2.헤더
'''#을 1개부터 6개까지 6단계로 사용할 수 있습니다.'''
# java
## html
### css
#### javascript
##### JSP
###### spring

### 1. 문단 구분을 위한 개행
여름 공원을 걸어 보아요.
  (개행: sapce 2개)
    여름을 만끽 하세요
