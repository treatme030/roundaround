<img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">

## 💋 roundaround 사이트 따라 만들어보기 
https://treatme030.github.io/roundaround
 * grid-template-areas를 이용한 아이템 레이아웃
 ```javascript
 .moment-container .moments-item-box .item-box {
    display: grid;
    height: 714px;
    grid-template-areas:
        "item-img1 more-info item-img3 item-img4"
        "item-img1 more-info using using"
        "item-img1 item-img2 using using"
        "item-img1 item-img2 copy copy";
    grid-template-columns: 588px 228px 192px 192px;
    grid-template-rows: 192px 294px 90px 138px;
}
```
 * background-attachment를 이용한 배경이미지 고정

![pro](https://user-images.githubusercontent.com/74355328/147443418-272ab283-41fc-4f34-8b6a-5c3899ab5905.gif)
