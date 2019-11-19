### [Project 5 : Classification](https://inst.eecs.berkeley.edu/~cs188/su19/project5/)
Trong project có 6 question cần thực hiện:

#### [Question 1 (4 points): Perceptron](http://ai.berkeley.edu/classification.html#Q1)
**Yêu cầu:** Hoàn thành hàm `train` trong file `perceptron.py`

**Hướng giải:** 
Viết các phép tính dựa vào công thức đã đưa ra trong q1.

#### [Question 2 (1 points): Perceptron Analysis](http://ai.berkeley.edu/classification.html#Q2)
**Yêu cầu:** Hoàn thành hàm `findHighWeightFeatures(self, label)` trong file `perceptron.py`. Nó trả về list 100 features với trọng số 
cao nhất cho label đó.

**Hướng giải:**
Sắp xếp các features theo thứ tự giảm dần rồi lấy 100 features đầu tiên.

#### [Question 3 (6 points): MIRA](http://ai.berkeley.edu/classification.html#Q3)
**Yêu cầu:** Viết hàm `trainAndTune` trong `mira.py`

**Hướng giải:** Viết các hàm, các phép toán theo như công thức đã được đưa ra cho Q3.
 
 #### [Question 4 (6 points): Digit Feature Design](http://ai.berkeley.edu/classification.html#Q4)
 **Yêu cầu:** Thêm mới các features nhị phân cho tập dữ liệu số trong hàm `EnhancedFeatureExtractorDigit` ở `dataClassifier.py`
 
 **Hướng giải:** 
 
 #### [Question 5 (4 points): Behavioral Cloning](http://ai.berkeley.edu/classification.html#Q5)
 **Yêu cầu:** Viết hàm `train` trong file 'perceptron_pacman.py'
 
 **Hướng giải:** Viết code tương tự như Q1.

 #### [Question 6 (4 points): Pacman Feature Design](http://ai.berkeley.edu/classification.html#Q6)
 **Yêu cầu:** Thêm mới các features cho behavioral cloning trong hàm `EnhancedPacmanFeatures ` ở file `dataClassifier.py`
 
 **Hướng giải:** Thêm các features `closestFood`, `closestGhost`, `remainingFood` để lưu trữ vị trí thức ăn gần nhất, 
 con ma gần nhất và số thức ăn còn lại trên bản đồ.
