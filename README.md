# amidakuji

[English](#whats-amidakuji)

[Japanese](#あみだくじって)

## What's Amidakuji?

Amidakuji (あみだくじ) is also known as "Ghost Leg" in Asia. [Ghost Leg - Wikipedia](https://en.wikipedia.org/wiki/Ghost_Leg)

 Japanese use Amidakuji when they decide something. They believe that Amidakuji is fairly and randomly way.

Is it true? I tested it.

## Definition of Amidakuji

Amidakuji composed of vertical line and horizontal line.

Vertical line is an array, and horizontal line is array replace in programing.

ex:

![image](https://user-images.githubusercontent.com/60678028/121023403-358c8200-c7de-11eb-94d1-7843d576293d.png)



### Step1 Make array.

[1, 2, 3, 4]

```python
def repoti(potision):
    potision = list(range(v_num ))
    #print(potision)
    return potision
```

### Step2 replace

[2, 1, 3, 4]
[2, 3, 1, 4]
[2, 1, 3, 4]
[2, 1, 4, 3]

```python
def swap(potision):
    s = random.randint(0,v_num-2)
    temp = potision[s]
    potision[s] = potision [s+1]
    potision [s+1] = temp
    #print(potision)
```

### Step3 End

result is [2, 1, 4, 3]

```python
sheet = pd.DataFrame(result)
sheet.to_csv("result.csv")
```

## what I do?

I tested 10000 time.

I find that amidakuji is not randomly.

So. if you play Amidakuji, you should choose right over that you want.



---



----

## あみだくじって？

あみだくじとは、アジアではGhost Legとも呼ばれています。

日本人はよく、何かを決定するときにこれを用いています。(用いてますよね？)また、みんなこれが公平で、ランダムなものと信じています。

ほんとうでしょうか。検証します。

## あみだくじの定義

あみだくじは縦棒と横棒で構成されています。

縦棒は配列で、横棒はその置換と捉えることができます。

例:

![image](https://user-images.githubusercontent.com/60678028/121023403-358c8200-c7de-11eb-94d1-7843d576293d.png)



### Step1 配列を作る

[1, 2, 3, 4]

```python
def repoti(potision):
    potision = list(range(v_num ))
    #print(potision)
    return potision
```

### Step2 置換

[2, 1, 3, 4]
[2, 3, 1, 4]
[2, 1, 3, 4]
[2, 1, 4, 3]

```python
def swap(potision):
    s = random.randint(0,v_num-2)
    temp = potision[s]
    potision[s] = potision [s+1]
    potision [s+1] = temp
    #print(potision)
```

### Step3 終わり！

result is [2, 1, 4, 3]

```python
sheet = pd.DataFrame(result)
sheet.to_csv("result.csv")
```



## 何をしたの？

一万回試しました。

あみだくじは完全にランダムではありませんでした。

あたりの真上を取るといいですね。
