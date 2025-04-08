# Healthy Weight Analyzer 🩺

A mobile app built with **React Native** (Expo) to help **doctors** quickly calculate a patient’s **BMI** and determine **how much weight they need to lose or gain** to fall within a healthy weight range based on height and weight inputs. While users can enter weight in **lb or kg**, all results are automatically converted and displayed in **kilograms (kg)** to maintain standard medical units.

## 📱 Features

- ✅ Input weight in **lb or kg** with automatic conversion to kg
- ✅ Input height in **feet/inches**
- ✅ **Real-time BMI calculation**
- ✅ Shows **minimum and maximum healthy weight** based on standard BMI range (18.5 – 24.9)
- ✅ Tells users **how much weight they need to lose or gain** in kg
- ✅ All output is displayed in **standard medical units (kg)** regardless of input
- 🚀 Coming soon: **Visual BMI trends with charts**

## 🧠 BMI Formula Used
\[
\text{BMI} = \frac{\text{Weight (kg)}}{(\text{Height (m)})^2}
\]

## 💻 Tech Stack

- **React Native** with Expo
- **JavaScript**
- **React Navigation**
- **Styled Components** *(optional)*
- **Victory Native** *(planned)* – for BMI chart visualization

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/healthy-weight-analyzer.git
cd healthy-weight-analyzer
