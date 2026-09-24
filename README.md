# 115-3a

> Markdown 基礎語法練習
> 國立高雄科技大學 資訊管理系

---

## 一、標題

# 一級標題 H1
## 二級標題 H2
### 三級標題 H3
#### 四級標題 H4
##### 五級標題 H5
###### 六級標題 H6

---

## 二、文字樣式

**這是粗體字**

*這是斜體字*

~~這是刪除線~~

***這是粗體加斜體***

這是 `行內程式碼` 的效果

---

## 三、列表

### 無序列表

- 1
- 2
- 3

### 有序列表

4. 4
5. 5
6. 6

---

## 四、引言區塊

> 巢狀
>>巢巢狀
>>>巢巢巢狀

---

## 五、程式碼區塊

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Markdown")
```

```sql
SELECT student_id, name
FROM students
WHERE department = '彪哥';
```

---

## 六、連結

[國立高雄科技大學](https://www.nkust.edu.tw)

---

## 七、圖片


![地科所](logo.svg "拉玩了")


---

## 八、表格

| 課程名稱 | 學分 | 成績 | 學期 |
|---|:---:|:---:|---:|
| 系統分析與設計 | 3 | F- | 115-1 |
| 存在與虛無 | 3 | F- | 114-1 |
| 睡覺 | 3 | A++ | 113-2 |

對齊方式：第一欄靠左、第二三欄置中、第四欄靠右。

---

## 九、嵌入影片

點擊縮圖即可前往影片頁面：

[![Markdown 教學](https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Kaohsiung_Love_River_IMG_2728.JPG/320px-Kaohsiung_Love_River_IMG_2728.JPG)](https://www.markdownguide.org "Markdown 完整教學")

語法結構為 `[![替代文字](縮圖網址)](影片網址 "標題")`，若要嵌入 YouTube 影片，縮圖網址可使用 `https://img.youtube.com/vi/影片ID/0.jpg`。

---

## 十、其他語法

### 分隔線

用三個連字號 `---` 獨占一行，就是上面那些橫線。

### 待辦清單

- [x] 學會標題與文字樣式
- [x] 學會列表與引言區塊
- [x] 學會程式碼區塊
- [ ] 練習更多進階語法
