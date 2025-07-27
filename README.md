# DesiBiteHub
Project that helps connect Street Food sellers and Vendors
# DesiBiteHub" = A central platform where authentic Indian street food (bites) and vendors connect."

## Project Description
DesiBiteHub is an intelligent, AI-powered platform designed to bridge the gap between street food vendors and food lovers in a culturally rich and tech-driven way. In an era where convenience, visibility, and digital engagement define consumer choices, DesiBiteHub revolutionizes the way people discover, experience, and support local street food vendors.

Our platform celebrates the vibrancy of desi street food culture by connecting small-scale vendors to a wider audience through smart location mapping, real-time stall updates, and personalised food recommendations powered by AI. From tracking your favourite chaat wala to finding the nearest hygienic thela, DesiBiteHub enhances the accessibility and visibility of local food gems while digitally empowering vendors.

With features like AI-based stall discovery, digital menus, customer feedback integration, QR-based payment support, vendor analytics, and raw material sourcing through community bidding, DesiBiteHub supports both customers and vendors in creating a seamless and flavourful street food experience. Whether you’re a foodie hunting for your next spicy bite or a vendor aiming to grow your reach, DesiBiteHub is your go-to platform for exploring India’s bustling food streets – one bite at a time.



## Why DesiBiteHub?
- **Supply Chain Gap**:  Street food vendors struggle to access affordable, quality raw materials consistently
- **Lack of Vendor Networks**:  Individual sellers lack a central platform to connect with trusted suppliers in their locality
- **Unstable Pricing**: Vendors face fluctuating market rates without collective bargaining power or price transparency
- **Language Accessibility**: Many financial tools lack support for Indian languages, limiting accessibility
- **Decision Support**: Users need contextual guidance for making better financial choices
- **Community Isolation**:  Street food sellers operate independently with minimal collaboration or support from peer communities

## Features

### Core Features
- **Smart Dashboard**: Interactive visualizations of spending patterns, budget status, and financial insights with real-time updates
- **QR-Based Ordering & Payments**: Automatically extract and categorize data from uploaded receipts and QR using computer vision and OCR
- **Intelligent Categorization**: Smart classification of transactions with raw materials with machine learning algorithms that improve over time
- **Raw Material Bidding System**: Vendors post ingredient needs, and local suppliers bid with competitive prices.

- **Predictive Analytics**: Forecast future expenses based on historical spending patterns and seasonal trends

### User Experience
- **Personalized Financial Assistant**: AI chatbot providing contextual financial advice based on spending habits
- **Budget Management**: Set, track, and receive alerts on custom budget categories with progress tracking
- **Savings Goals**: Define and visualize progress toward financial objectives with milestone celebrations
- **Multi-Language Support**: Interface available in English, Hindi, Malayalam, and Kannada for wider accessibility
- **Community Market Exchange**: Vendor-to-vendor marketplace for ingredient swaps and bulk group purchases.

## How It Works
1. **Data Collection**: Users connect accounts or manually upload receipts through our OCR system
2. **AI Processing**: Our algorithms analyze transaction data, categorize expenses, and identify patterns
3. **Insight Generation**: The system transforms raw data into actionable financial insights and visualizations
4. **Personalized Recommendations**: Based on spending patterns, BudgetIQ provides tailored financial advice
5. **Continuous Learning**: The system improves over time by learning from user interactions and feedback

## Technology Stack

### Frontend
- **Core**: React, TypeScript, Tailwind CSS
- **UI Components**: Shadcn UI, Framer Motion
- **Data Visualization**: Recharts, D3.js
- **State Management**: React Query, Context API
- **Routing**: React Router

### Backend
- **Server**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Real-time Features**: Socket.io
- **Caching**: Redis

### AI/ML
- **Core ML**: TensorFlow.js
- **Natural Language Processing**: For financial assistant and transaction categorization
- **Computer Vision**: OpenCV, Tesseract OCR for receipt processing
- **Predictive Models**: Custom algorithms for expense forecasting

### Cloud Infrastructure
- **Services**: AWS Lambda, Amazon S3
- **CI/CD**: GitHub Actions
- **Deployment**: Vercel

## Challenges We Faced

- **Receipt Analysis Complexity**: Developed custom preprocessing pipelines to handle varied receipt formats, fonts, and layouts
- **Multi-Currency Integration**: Created a reliable exchange rate system with fallbacks for accurate currency conversions
- **AI Knowledge Base Development**: Balanced hardcoded financial knowledge with dynamic, context-aware responses
- **Language Localization**: Accurately translated complex financial terminology across multiple Indian languages
- **Performance Optimization**: Enhanced rendering efficiency for data-intensive dashboards across various devices
- **Mobile UI Adaptation**: Designed adaptive visualizations that transform based on screen size without losing functionality
- **Security Implementation**: Built robust protection measures for sensitive financial data with end-to-end encryption
- **Deployment Constraints**: Unable to deploy due to hosting platform limitations that only supported HTML, CSS, and JavaScript while working within budget constraints

## Future Scope

- **Banking API Integration**: Direct connection with banking systems for automatic transaction import
- **Advanced Predictive Models**: Enhanced AI predictions for long-term financial planning and scenario analysis
- **Investment Portfolio Tracking**: Comprehensive investment management with performance analytics
- **Collaborative Budgeting**: Family and group budget management with shared access controls
- **Gamification System**: Expanded reward system to encourage positive financial habits
- **Voice Command Interface**: Natural language processing for hands-free operation
- **Financial Education Hub**: Personalized learning resources based on user's financial knowledge gaps
- **Expanded Language Support**: Additional regional Indian languages to increase accessibility

## Team Members

HARINI.P- FULLSTACK DEVELOPER
RAKSHITA- CHATBOT AND PREDICTIVE ANALYSIS
DHESHNA.B-API INTEGRATION AND NLP

## 📋 Installation and Setup

### Prerequisites

- Node.js (v16+)
- npm or yarn
- MongoDB (local or Atlas connection)

### Local Development

1. Clone the repository
   ```bash
   git clone https://github.com/expertise03/Budgetiq
   cd expertise03
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   S3_BUCKET=your_s3_bucket_name
   AWS_ACCESS_KEY=your_aws_access_key
   AWS_SECRET_KEY=your_aws_secret_key
   ```

4. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## 📊 Project Screenshots


## Hashtags
##Communitybased ##StreetFood ##Transactionhistory ##Biddingsystem ##Qualitycheck ##AIPrediction

 
