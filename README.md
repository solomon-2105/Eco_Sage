# **EcoSage** 🌱

**EcoSage** is an intelligent Chrome extension and backend service that analyzes the **eco-friendliness** of products listed on popular e-commerce platforms like **Amazon** and **Flipkart**. By leveraging cutting-edge AI, it provides insights into the environmental impact of the products you browse, helping you make informed and sustainable purchasing decisions.

## 🚀 **Features**
- **Eco Analysis**: Analyze product descriptions to get an **eco-friendliness score** (1-5).
- **Environmental Concerns**: Discover the main environmental concerns associated with the product.
- **Sustainable Alternatives**: Get suggestions for better, more eco-friendly alternatives (when applicable).
- **Seamless Experience**: Works directly on Amazon and Flipkart product pages with a side panel that provides real-time results.

## 🛠️ **Tech Stack**
- **Frontend**:  
  - **Chrome Extension**: HTML, CSS, JavaScript  
- **Backend**:  
  - **Flask**: For API handling and communication  
  - **Gemini API**: To analyze the product descriptions and determine eco-friendliness  
  - **Python**: Core backend logic

## 🔌 **How It Works**
1. **Frontend** (Chrome Extension):
   - Instantly analyzes product descriptions from **Amazon** and **Flipkart**.
   - Displays an eco-friendliness score and analysis in a side panel on the product page.
   - Sends product data to the backend for processing.

2. **Backend**:
   - **Flask-based API**: Receives product descriptions from the frontend.
   - **Gemini API**: Analyzes the environmental impact of the product.
   - Returns results with a detailed eco-friendliness score and environmental concerns.

