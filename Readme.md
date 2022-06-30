
# Αναγνώριση Συναισθημάτων από το Ψηφιακό Σήμα της Ομιλίας

Για τα πειράματα της πτυχιακής εργασίας χρησιμοποιήθηκαν jubyter notebook κ συγκκριμένα  Google Colab notebooks. Υπάρχουν 5 Notebooks και στο καθένα αναγράφεται η ενότητα που του αντιστοιχεί στο pdf του report της πτυχιακής.

## Χρήση

Για την χρήση του κώδικα της εργασίας προτείνεται τα notebooks να τρέξουν στο google colab με την χρήση gpu, διαφορετικά ο χρόνος εκτέλεσης μεγαλώνει απαγορευτικά.

Για την ενεργοποιήση της GPU στο google colab εκτελούμε τα παρακάτω βήματα:
- Navigate to Edit→Notebook Settings
- select GPU from the Hardware Accelerator drop-down

Αφού οριστεί η gpu πρέπει να ορισθούν τα paths των αρχείων που και αυτα πρέπει να είναι στο google drive.  Τα paths αυτά στο drive (μου) συμφωνά με τον φάκελο που έχει γίνει [share στο google drive](https://drive.google.com/drive/folders/18Ab_vP9_hj8nVcgAigthgJEw_rygGy-v?usp=sharing) είναι:
- annotations_path_arousal = "/content/drive/MyDrive/Πτυχιακή/Recolla Data/RECOLA-Annotation/emotional_behaviour/arousal/"
- annotations_path_valence = "/content/drive/MyDrive/Πτυχιακή/Recolla Data/RECOLA-Annotation/emotional_behaviour/valence/"
- wavs_path = "/content/drive/MyDrive/Πτυχιακή/Recolla Data/RECOLA-Audio-recordings-norm-6segments/"

Καλο θα ήταν τα αρχεία αυτα να είναι στον ίδιο λογαριασμό google στον οποίο τρέχει και το google colab.

## Απαραίτητα πακέτα

Εφόσον τα notebooks τρέχουν στο google colab δεν χρειάζεται να κατέβει κανένα πακέτο καθώς το colab έχει προεγκατεστημένα τα περισσότερα και τα υπόλοιπα θα εγκατασταθούν αυτόματα με το pip.

Διαφορετικά πρεπεί να εγκατασταθούν τα εξής μεσω pip:
- keras==2.8.0
- librosa==0.9.1
- matplotlib==3.5.2
- numpy==1.22.3
- pandas==1.4.2
- preprocess==2.0.0
- protobuf==4.21.2
- scipy==1.8.0
- seaborn==0.11.2
- tensorflow==2.8.0

Μπορουν να εγκατασταθούν αυτόματα τρέχοντας  την εντολή :
```
pip install -r requirements.txt

```
οπού το requirements.txt υπάρχει μέσα στο φάκελο code.
