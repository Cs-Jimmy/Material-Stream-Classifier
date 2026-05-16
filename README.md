# Material Stream Identification System

Cairo University — Faculty of Computing and Artificial Intelligence
Machine Learning Course — Final Project

| ID | Class     | Description                                       |
|----|-----------|---------------------------------------------------|
| 0  | Cardboard | Multi-layer cellulose fiber material              |
| 1  | Glass     | Bottles, jars, amorphous silicates                |
| 2  | Metal     | Aluminum cans, steel scrap                        |
| 3  | Paper     | Newspapers, office paper                          |
| 4  | Plastic   | Water bottles, film, organic compounds            |
| 5  | Trash     | Non-recyclable / contaminated waste               |
| 6  | Unknown   | Out-of-distribution or blurred inputs (rejection) |

---

## Setup

```bash
pip install -r requirements.txt
```

## Run Order

1. Unzip `dataset.zip` into the project root
2. Run `src/1. data_aug.ipynb`
3. Run `src/2. feature_extraction.ipynb`
4. Run `src/SVM_Model.ipynb` and `src/KNN_Model.ipynb`
5. Run the camera app:

```bash
python src/camera_app.py
```

Press **Q** to quit.

---

## Team

| Name | ID |
|------|----|
| Martina Waleed Salah | 20237010 |
| Laila Mohamed Shawky | 20236076 |
| Jumanah Muhammad Ali | 20237003 |
| Malak Moustafa Abdel-Maboud | 20237015 |
| Basmala Mohsen El-Batran | 20237020 |

TA: Eng. Ahmed Samir
