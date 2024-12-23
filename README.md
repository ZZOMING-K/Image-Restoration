# Image-Restoration

손실된 이미지의 특정 영역을 복구하고 흑백 이미지에 적합한 색을 입혀 원본과 유사한 이미지를 재창조하는 알고리즘 개발 

## 🔥 시도 
[Image Inpainting SOTA Model](https://paperswithcode.com/sota/image-inpainting-on-places2-1)

**시도1** 

**시도2**


## 😎 대회 참여 회고
* `pytorch`에 더 익숙해지기 위해서 참여한 대회였습니다.
* Image Restoration분야의 SOTA 모델을 조사하고, 논문을 읽으며 해당 레포지토리를 참고하여 구현해 구현을 시도했었습니다. 그러나 모델 적용이 쉽지 않은 부분들이 많았습니다.

  * 사전학습된 모델이 없는 경우에는 **모델을 활용할 수 없다는 한계**.
  * 최신 SOTA Image Restoration 모델들은 **손실 이미지의 MASK 데이터를 필요**로 하지만, MASK 데이터가 없는 경우 이를 어떻게 생성할 것인지에 대한 고민.
  * 코드의 정확성에 대한 불확실성과 **한 번의 학습에 많은 리소스가 요구**되어 방향성을 설정하는 데 부담
           
* **U-Net 모델**에 대해 더 깊은 이해를 할 수 있는 기회가 되었습니다. 
* 단시간에 빠르게 결과를 내야 하는 상황에서는 **Vast.ai** 를 활용할 수 있다는 점을 새롭게 알게 되었습니다.
* 앞으로 대회에 자주 참여하여 pytorch에 더욱 능숙해지고, 논문을 직접 코드로 구현할 수 있는 능력을 키워나가야겠습니다.  

## ⭐ 1위 Solution 살펴보기 
* SAM(MASK 생성)+ MAT(Image Restoration) +DDColor(Colorization)
