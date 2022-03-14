# Heart Failure Prediction Using Ensemble Learning
Dalam dataset riawyat kesehatan pasien dengan gangguan kardiovaskular, diperlukan model yang dapat **memprediksi** apakah pasien tersebut akan meninggal sebelum dilakukan _follow up check_.

**PROBLEM DEFINITION**
- Goal: membuat model yang memberikan **prediksi** apakah pasien akan meninggal sebelum menjalani _follow up check_ berikutnya atau tidak.
- Problem merupakan _classification problem_ dengan _outcome_ **_binary_** (yes / no, 1 / 0).
- Membuat model yang dapat memberikan prediksi dengan baik, dengan error seminimal mungkin.
- Feature - feature dalam dataset dianggap memiliki bobot yang sama dalam menentukan _outcome_ prediksi. Tidak akan dikalkulasi bagaimana hubungan feature dengan outcome.
- Dalam prediksi apakah pasien lebih berkemungkinan untuk tetap hidup atau meninggal, selain nilai **akurasi** yang baik, diinginkan pula nilai **recall** / _sensitivity_ dari model yang lebih tinggi dari nilai _precision_. Lebih diinginkan prediksi akan meninggal yang benar agar pasien dan keluarganya dapat diinformasikan mengenai kondisi medisnya dan kemungkinan terburuk. Namun nilai **_precision_** yang baik juga diharapkan agar memastikan probabilitas pasien yang masih akan hidup diklasifikasikan sebagaimana mestinya.

## Link to the Dataset
https://www.kaggle.com/andrewmvd/heart-failure-clinical-dat
