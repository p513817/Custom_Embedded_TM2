# Custom_Embedded_TM2
change method of video stream from the original to opencv and let EmbeddedTM2 could reload data.

[![Embedded Teachable Machine ( Custom )](https://res.cloudinary.com/marcomontalbano/image/upload/v1624946100/video_to_markdown/images/youtube--7Q_5GWvCZFM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=7Q_5GWvCZFM "Embedded Teachable Machine ( Custom )")

# 介紹
Embedded Teachable Machine是Google在推出Coral USB Accelerator時所設計搭配的一個小專案，可透過按鈕來執行拍照並且即時進行圖片分類，少量的資料就可以完成訓練，此篇除了介紹、使用之外也嘗試修改成OpenCV的方式去運行，並加入了重新載入資料的功能。更多詳細介紹請至[此處](https://www.rs-online.com/designspark/google-coral-usb-acceleratorraspberry-pi4embedded-teachable-machine-2-cn)

# 程式
| 程式  | 描述  |
| --- | --- |
| [teachable.py](./code/teachable.py) | 原本的程式 |
| [teachable_reload.py](./code/teachable_reload.py) | 加入重新載入資料的功能  |
| [teachable_withCV.py](./code/teachable_withCV.py) | 修改成透過OpenCV讀取的方式  |

# 影片介紹

## Embedded Teachable Machine ( Original )

[![Embedded Teachable Machine ( Original )](https://res.cloudinary.com/marcomontalbano/image/upload/v1624945933/video_to_markdown/images/youtube--hR5SwGqrCps-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=hR5SwGqrCps "Embedded Teachable Machine ( Original )")

## Embedded Teachable Machine ( Custom )

[![Embedded Teachable Machine ( Custom )](https://res.cloudinary.com/marcomontalbano/image/upload/v1624946100/video_to_markdown/images/youtube--7Q_5GWvCZFM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=7Q_5GWvCZFM "Embedded Teachable Machine ( Custom )")
