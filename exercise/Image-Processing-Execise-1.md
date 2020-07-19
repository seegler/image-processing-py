### Dependencies

* **Anaconda**
* **OpenCV**

```
conda install -c menpo opencv
#test by "import cv2"
```


```python
import cv2
from PIL import Image
```

### cv2.imread, cv2.imshow 
read and show image


```python
img = cv2.imread("assets/end-detour.jpg")
cv2.imshow("Image", img)
cv2.waitKey(0)
```


```python
cv2.destroyAllWindows()
```


```python

```
