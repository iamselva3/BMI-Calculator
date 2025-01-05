### BMI Calculator Project

This **BMI (Body Mass Index) Calculator** is a simple web-based tool that helps users calculate their Body Mass Index based on their weight and height. The application calculates BMI using the metric system (kilograms and centimeters) and provides an interpretation of the result in terms of BMI categories like **Obese**, **Overweight**, **Normal**, or **Underweight**.

### Features:
1. **Input Fields**:
   - Users can input their **weight** in kilograms and **height** in centimeters.
   
2. **Real-Time Calculation**:
   - The app calculates the BMI instantly as the user enters values for weight and height.
   
3. **BMI Categorization**:
   - The app categorizes the BMI into one of four categories:
     - **Obese** (BMI ≥ 30)
     - **Overweight** (BMI between 25.0 and 29.9)
     - **Normal** (BMI between 18.5 and 24.9)
     - **Underweight** (BMI ≤ 18.4)
   - The category is displayed along with the corresponding color styling.

4. **Dynamic UI Updates**:
   - The displayed BMI value is updated in real-time based on the user input.
   - The category label changes color depending on the BMI value to give a visual cue (e.g., red for "Obese", blue for "Normal").

## How It Works:
1. **User Input**: The user provides their weight (in kilograms) and height (in centimeters) using the input fields.
2. **BMI Calculation**: The app uses the formula `BMI = weight / height²`, where weight is in kilograms and height is in meters squared (height in centimeters is first converted to meters).
3. **Category Check**: Based on the calculated BMI, the app assigns a category (Obese, Overweight, Normal, or Underweight) and displays it on the screen.
4. **UI Updates**: As the user enters new values, the BMI is recalculated, and the corresponding category and BMI value are updated in real-time.

### Technologies Used:
- **HTML**: For structuring the input fields and displaying the BMI result.
- **CSS**: For styling the application and creating a visually appealing design.
- **JavaScript**: For calculating BMI, categorizing the result, and dynamically updating the user interface.

### Purpose:
This project helps users quickly assess their body mass index and get an idea of their weight status based on established BMI categories. It is a practical tool for personal health tracking and education.
