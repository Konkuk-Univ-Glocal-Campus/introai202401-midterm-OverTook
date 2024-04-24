중간고사: 컴퓨터 비전 문제
목표: 간단한 컨볼루션 신경망(CNN)을 사용하여 이미지 분류 작업을 수행합니다. 이 과제에서는 Fashion-MNIST 데이터셋을 사용합니다. Pytorch로 구현하세요.
학습관리시스템에 자신의 Python 코드와 데이터 파일이 저장된 github classroom repository link를 제출하시오 (코드는 github codespace에서 실행되어야 함)
과제 마감: 04.25 (목) 10:30

<h1><b>모델 성능 (훈련 단계)</b></h1>

<b>Epoch: 01<br></b>
train loss = 0.598 train accuracy = 77.865 <br>
validation loss = 0.358 validation accuracy = 86.378<br>
<b>Epoch: 02<br></b>
train loss = 0.398 train accuracy = 85.602<br>
validation loss = 0.297 validation accuracy = 89.167<br>
<b>Epoch: 03<br></b>
train loss = 0.350 train accuracy = 87.498<br>
validation loss = 0.277 validation accuracy = 89.844<br>
<b>Epoch: 04<br></b>
train loss = 0.317 train accuracy = 88.463<br>
validation loss = 0.259 validation accuracy = 90.267<br>
<b>Epoch: 05<br></b>
train loss = 0.294 train accuracy = 89.235<br>
validation loss = 0.234 validation accuracy = 91.200<br>
<b>Epoch: 06<br></b>
train loss = 0.278 train accuracy = 89.967<br>
validation loss = 0.227 validation accuracy = 91.456<br>
<b>Epoch: 07<br></b>
train loss = 0.263 train accuracy = 90.376<br>
validation loss = 0.217 validation accuracy = 92.100<br>
<b>Epoch: 08<br></b>
train loss = 0.249 train accuracy = 90.969<br>
validation loss = 0.211 validation accuracy = 92.456<br>
<b>Epoch: 09<br></b>
train loss = 0.240 train accuracy = 91.096<br>
validation loss = 0.209 validation accuracy = 92.489<br>
<b>Epoch: 10<br></b>
train loss = 0.232 train accuracy = 91.537<br>
validation loss = 0.205 validation accuracy = 92.478<br>
<b>Epoch: 11<br></b>
train loss = 0.220 train accuracy = 91.804<br>
validation loss = 0.199 validation accuracy = 92.856<br>
<b>Epoch: 12<br></b>
train loss = 0.219 train accuracy = 91.808<br>
validation loss = 0.205 validation accuracy = 92.478<br>
<b>Epoch: 13<br></b>
train loss = 0.215 train accuracy = 92.027<br>
validation loss = 0.199 validation accuracy = 93.033<br>
<b>Epoch: 14<br></b>
train loss = 0.202 train accuracy = 92.380<br>
validation loss = 0.199 validation accuracy = 92.567<br>
<b>Epoch: 15<br></b>
train loss = 0.203 train accuracy = 92.510<br>
validation loss = 0.197 validation accuracy = 92.744<br>
<b>Epoch: 16<br></b>
train loss = 0.195 train accuracy = 92.702<br>
validation loss = 0.193 validation accuracy = 93.111<br>
<b>Epoch: 17<br></b>
train loss = 0.189 train accuracy = 92.998<br>
validation loss = 0.194 validation accuracy = 93.133<br>
<b>Epoch: 18<br></b>
train loss = 0.188 train accuracy = 92.959<br>
validation loss = 0.194 validation accuracy = 93.000<br>
<b>Epoch: 19<br></b>
train loss = 0.184 train accuracy = 93.037<br>
validation loss = 0.189 validation accuracy = 93.278<br>
<b>Epoch: 20<br></b>
train loss = 0.181 train accuracy = 93.127<br>
validation loss = 0.195 validation accuracy = 92.956<br>


<h1><b>모델 성능 (최종 Test)</b><br></h1>
Test Accuracy: 92.63<br>
Test Loss: 0.21479549486735824<br>

<h1>Accuracy 변화</h1>
<img src="https://github.com/Konkuk-Univ-Glocal-Campus/introai202401-midterm-OverTook/assets/20220857/cccbe4cf-5ed7-4fcb-998f-b6ad35982947"></img>
Epoch가 20에 가까워짐에 따라 Train 정확도, Validation 정확도가 점차 상승하는 모습을 볼 수 있다.<br>
하지만 일정 수준 이상으로 상승하면 정확도에 변동이 거의 없어진다.

<h1>Loss 변화</h1>
<img src="https://github.com/Konkuk-Univ-Glocal-Campus/introai202401-midterm-OverTook/assets/20220857/58ae52de-6878-4a61-a4d9-f2afde0e7a2e"></img>
Epoch가 20에 가까워짐에 따라 Train Loss, Validation Loss가 점차 하강하는 모습을 볼 수 있다.<br>
하지만 일정 수준 이상으로 상승하면 정확도에 변동이 거의 없어진다.

<h1>잘못 분류된 이미지</h1>
<a href="https://github.com/Konkuk-Univ-Glocal-Campus/introai202401-midterm-OverTook/blob/main/mid_term.ipynb">페이지 이동</a><br>
페이지 내부 #13 에 기재되어 있습니다. (데이터 양이 많습니다!)
