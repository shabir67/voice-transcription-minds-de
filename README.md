# **Project Overview**

## **Dataset**
- **Minds/14 De (Deutsch)**
- **Task**: Intent Classification & Transcription

### **Intent Classification Model**: `superb/hubert-base-superb-ks`
- **Accuracy**: 0.0406
- **F1 Score**: 0.0055
- **Loss**: 2.655

## **Voice Transcription Model**: `openai/whisper-small`

### **Advanced Preprocessing & Data Augmentation**
- **Word Error Rate (WER)**: 0.179563%
- **Inference Time**: 1.0117 seconds

### **Standard Preprocessing**
- **Word Error Rate (WER)**: 15.456238%
- **Inference Time**: 1.3529 seconds

### **Bare Metal Fine-Tuning**
- **Word Error Rate (WER)**: 15.641476%
- **Inference Time**: 0.5741 seconds

## **Conclusion**
- **Best Model**: Advanced Preprocessing and Data Augmentation (`whisper-small`)
- **Fastest Inference**: Bare Metal Fine-Tuning (0.5741 seconds)
