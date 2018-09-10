# 네이버 AI 해커톤 2018

"한계를 넘어 상상에 도전하자!"

인간이 오감을 활용하는 것처럼 AI도 인간의 오감을 모두 활용하는 방향으로 나아갈 것입니다.<br>
또한, 인터넷과 모바일이 세상을 크게 변화시킨 것처럼 AI 역시 세상을 크게 변화시킬 것이며 그 영향력은 더욱 커질 것입니다.<br>
네이버는 AI와 함께 더 편리하고 행복한 미래를 만들기 위해 **네이버 AI 해커톤 2018**을 준비했습니다.<br>

특히, 이번 네이버 AI 해커톤 2018은 네이버의 클라우드 머신러닝 플랫폼인 <strong>[NSML](https://hack.nsml.navercorp.com/intro)</strong>과 함께 합니다.

<strong>NSML(Naver Smart Machine Learning)</strong>은 모델을 연구하고 개발하는 데 필요한 복잡한 과정을 대신 처리해주어<br>
연구 개발자들이 "모델 개발"에만 전념할 수 있고, 다양한 시도를 쉽게 할 수 있는 창의적인 환경을 제공할 것입니다.

AI를 통해 복잡한 문제를 해결하고 싶나요?<br>
AI 전문가들과 함께 문제 해결 방법을 고민하고 경험을 공유하고 싶다고요?

지금 바로 <strong>네이버 AI 해커톤 2018</strong>에 참여해서<br>
서로의 경험을 공유하고, 다양하고 창의적인 방법으로 문제를 해결해 보세요!

[안내 및 문제 소개](https://youtu.be/cSGPHtzPFQw)


# 영화 평점 예측

**보고 싶고 알고 싶은 영화의 모든 것! 네이버 영화 평점을 예측해 보세요!**

네이버 영화는 영화 정보, 영화 평, 영화 인물 정보를 한 눈에 볼 수 있고, 영화 예매까지 한꺼번에 할 수 있어서 많은 분들이 좋아하는 서비스입니다. 특히 네이버 영화 평점은 개봉 전 영화에 대한 기대평이나 개봉작에 대한 관람 후 평가를 등록하는 기능입니다. 140자 평과 함께 평점을 등록할 수 있어 영화를 좋아하는 많은 사람이 참고하는 정보가 되고 있습니다.

영화와 처음 만나는 곳! 네이버 영화는 어떻게 하면 더 신뢰할 수 있는 평점을 제공할 수 있을까 항상 고민하고 있습니다. 어떠한 영화 평을 작성했을 때 그 영화 평에 가장 합당한 평점을 예측할 수 있다면 더 객관적이고 신뢰할 수 있는 평점이 되지 않을까요?

여러분은 이를 위해 기존 영화 평과 평점을 학습해, 주어진 영화 평에 가장 알맞는 평점이 몇 점인지 예측하는 모델을 개발해야 합니다.

# 데이터 구조

| 영화 평 | 평점|
| ----- | ---- |
| 영화를 이루는 모든 요소가 완전하다 | 10 |
| 너무 흥미롭고 단 한순간도 지루할틈이 없었다 | 9 |
| 이해는 하나 공감은 할 수 없는 영화 | 7 |
| 진짜 이 영화 무슨 내용인지 모르겠네 | 2 |


# Model
Character Level Embedding + Bi-directional LSTM + multi-layer CNN + Fully connect layer
-> Code is private but you can see details with [my paper](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07503227)


# Score
Mse : 2.67
2ND price at final 






## License
```
Copyright 2018 NAVER Corp.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
