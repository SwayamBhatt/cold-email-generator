# Cold Email Generator for Service Companies

## Overview
This project is a **Cold Email Generator** for service companies seeking to connect with potential clients by proposing solutions to job openings. By utilizing **Groq**, **LangChain**, and **Streamlit**, the tool automates the process of generating cold emails tailored to specific job roles listed on a company's careers page. With an easy-to-use interface, users can input the URL of a target company's careers page, and the tool will identify relevant job listings and generate personalized email content.

## Key Features
- **Targeted Job Listing Extraction**: Automatically scrapes job postings from a given careers page URL.
- **Custom Email Generation**: Creates personalized emails tailored to the job role and company, using language that positions your company's services as an ideal solution.
- **Vector-Based Portfolio Matching**: Integrates relevant portfolio links by querying a vector database, ensuring each email includes portfolio items closely aligned with the job description.
- **Easy-to-Use Interface**: Built with Streamlit, allowing users to quickly generate and preview emails without coding knowledge.

## Use Case Scenario
Imagine Company-X, a software development service provider, wants to offer its services to Nike, which has an open position for a **Principal Software Engineer**. Instead of Nike spending valuable time and resources on hiring, onboarding, and training, Company-X proposes a dedicated engineer to fill this role. A business development executive, like Ben, can use this tool to input Nike's careers page URL. The tool then scrapes Nike's job listings, identifies the role of interest, and generates a compelling cold email for Ben to send to Nike's hiring team, complete with relevant portfolio links.

## Tech Stack
- **Groq**: For efficient job listing extraction and language understanding.
- **LangChain**: For natural language processing and cold email text generation.
- **Streamlit**: To provide a seamless, interactive front-end for users.
- **Vector Database**: (e.g., Pinecone or similar) to store and retrieve portfolio items relevant to the job description.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/cold-email-generator.git
   cd cold-email-generator
   ```

2. **Install Dependencies:**
   Ensure you have Python 3.7+ and then install the necessary packages.
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Vector Database**:
   Configure your vector database (e.g., Pinecone) and add your portfolio links and descriptions.

4. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open the app in your web browser.
2. Enter the URL of the target company's careers page.
3. View extracted job listings, select a role, and generate a customized email.
4. Preview and export the email for sending.

## Example

For Nike’s **Principal Software Engineer** role:
- Ben from Company-X inputs Nike's careers page URL.
- The tool identifies relevant job descriptions.
- It creates a personalized cold email suggesting how Company-X can support Nike's hiring needs by providing a dedicated software engineer.
- Relevant portfolio links are included to demonstrate Company-X’s expertise.

## Contributing
We welcome contributions to improve this project. Feel free to submit issues, feature requests, or pull requests.

## License
This project is licensed under the MIT License.

---

**This tool is intended to enhance business development outreach by creating tailored, professional emails, helping companies showcase relevant skills and experiences aligned with specific job needs.**
