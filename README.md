

# 📧 Cold Mail Generator

Welcome to the Cold Mail Generator! This tool is designed for service companies that want to streamline their outreach process. With the power of **Groq**, **LangChain**, and **Streamlit**, you can generate personalized cold emails by simply inputting the URL of a company’s careers page. The tool extracts job listings, matches portfolio links from a vector database to each listing, and generates tailored emails to fit each specific job description.

### 🔍 Use Case Scenario

**Imagine this:**  
Nike is looking to hire a Principal Software Engineer. Hiring, onboarding, and training takes time and resources. **Atliq**, a software development company, could provide Nike with a ready-to-go software engineer. Aditya, a business development executive at Atliq, uses this tool to generate a professional, personalized cold email, showcasing Atliq’s relevant experience and how they can meet Nike's needs right away.

![img.png](img.png)

---

## 🌟 Features

1. **Automatic Job Listings Extraction** – Just enter the URL of the company's careers page, and we handle the rest!
2. **Customizable Cold Emails** – Emails are generated based on the extracted job listings.
3. **Relevant Portfolio Links** – Each email includes portfolio links from a vector database that match the job requirements.

### 🛠 Architecture Overview

Our tool leverages **Groq** for data extraction, **LangChain** to structure and process information, and **Streamlit** for a seamless, interactive interface. Here’s a sneak peek:

## Architecture Diagram

![img.png](architecture.png)
---

## 🚀 Getting Started

Follow these steps to get started with the Cold Mail Generator:

### 1. Set Up Your API Key

To extract job data, you’ll need an API key from Groq.  
- [Get your API key here](https://console.groq.com/keys).
- Once you have it, open the `.env` file in the `app/` directory and paste your API key as follows:

  ```plaintext
  GROQ_API_KEY=your_api_key_here
  ```

### 2. Install Required Libraries

In your terminal, navigate to the project directory and run:

```bash
pip install -r requirements.txt
```

This command will install all the necessary libraries and dependencies.

### 3. Launch the Application

Start the Streamlit app with this command:

```bash
streamlit run app/main.py
```

Open the link displayed in your terminal to access the app.

---

## 🎯 How to Use

1. **Enter a Company URL** – Paste the careers page URL of the company you’re targeting.
2. **Generate Emails** – With a click, the tool extracts job listings and generates personalized emails.
3. **View & Customize** – Each email includes tailored content and relevant portfolio links. You can adjust the content before sending.

> **Pro Tip:** Experiment with different career pages to see how the tool adapts to various job listings and descriptions.

---

## 💡 Example Workflow

Let’s say Aditya from Atliq wants to reach out to Nike:

1. **Input Nike's Careers Page URL**: Aditya pastes the link to Nike’s job listings page.
2. **Generate Emails**: The tool pulls job titles and descriptions, crafting a personalized message for each job listing.
3. **Send Targeted Email**: Aditya receives a polished, tailored email that highlights Atliq’s relevant experience and includes portfolio links related to Nike’s job needs. This helps establish Atliq as a qualified partner.

---

## 🤝 Contributing

Contributions are always welcome!  
1. Fork the repo.
2. Create a new branch for your feature.
3. Make changes and submit a pull request.

---

## 🙋 Have Questions?

Feel free to open an issue or reach out if you have any questions, ideas, or feedback. We’re here to help and would love to hear from you!

Enjoy creating personalized cold emails with ease!
