# AIFFEL Campus Online 4th Code Peer Review Templete
- 코더 : 코더 1인의 이름을 작성하세요.
- 리뷰어 : 본인의 이름을 작성하세요.


# PRT(PeerReviewTemplate)
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.
- [x] 1.코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
- [x] 2.주석을 보고 작성자의 코드가 이해되었나요?
- [x] 3.코드가 에러를 유발할 가능성이 있나요?
  > 피어리뷰하면서 발생한 에러들을 같이 수정하여 같이 결과를 낼 수 있었습니다.
- [x] 4.코드 작성자가 코드를 제대로 이해하고 작성했나요?
  > 
- [x] 5.코드가 간결한가요?
  > 

```python
controlnets = [canny_controlnet, openpose_controlnet]
# 전처리기 불러올 때, 새롭게 다시 불러오는 것보다 이미 할당해 놓은 변수를 가져오는게
여러번 반복 실행했을 때 효율적이었습니다.
canny_image = canny_image.resize((640, 640))
openpose_image = openpose_image.resize((640, 640))
# 사이즈 오류가 발생해서 두 개의 이미지 사이즈를 맞춰주는 작업이 필요했습니다.
```
