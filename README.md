# OCR-Vietnamese

PP-OCR is a practical ultra-lightweight OCR system. It is mainly composed of two parts: CRAFT text detection and Transformer text recognition.

## Getting Started

```
git clone https://github.com/hoainv99/OCR-Vietnamese.git
cd OCR-Vietnamese
virtualenv env
source env/bin/activate
```

### Installing

	pip3 install opencv-python
	pip3 install torchvision
	pip3 install pyyaml
	pip3 install scipy

## Running the tests

To test image using:

```
python3 OCR.py --image_path test/test2.png

```
now, the result below:

![](test/test2.png)
```
([[295, 1], [329, 1], [329, 21], [295, 21]], 'TU')
([[85, 50], [610, 50], [610, 134], [85, 134]], 'SAM NẤM HÀN QUỐC')
([[342, 135], [505, 135], [505, 173], [342, 173]], 'Nấm linh chi')
([[196, 144], [328, 144], [328, 174], [196, 174]], 'Nhân Sâm')
([[435, 164], [556, 164], [556, 207], [435, 207]], 'Mỹ phẩm')
([[147, 173], [417, 173], [417, 216], [147, 216]], 'Thực phẩm chức năng')
([[531, 215], [615, 215], [615, 233], [531, 233]], '0968.629.886')
([[397, 216], [525, 216], [525, 237], [397, 237]], 'Hotline: 0968.189.123')
([[88, 224], [358, 224], [358, 248], [88, 248]], 'ĐC: 282 Trần Nguyên Hãn, Lê Chân, Hải Phòng')
([[655, 229], [685, 229], [685, 243], [655, 243]], '00')
([[26, 248], [50, 248], [50, 272], [26, 272]], 'km')
([[536, 310], [576, 310], [576, 318], [536, 318]], 'TẠIỆNH')
```
## Authors

* **Nguyen Viet Hoai** - [github](https://github.com/hoainv99)


## License

## Acknowledgments

