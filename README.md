# Email_Agent

---

This guide will walk you through setting up and running your `Email_Agent` project.

## 1. Project Setup

First, navigate to your project directory:

```bash
cd D:\Agents\crewAI-examples\email_auto_responder_flow
```

## 2. Set Up Virtual Environment

It's best practice to use a virtual environment to manage project dependencies.

### Create the Environment

```bash
python -m venv .venv
```

### Activate the Environment

```bash
.\.venv\Scripts\activate
```

## 3. Install Dependencies

Once your virtual environment is active, install all the necessary packages:

```bash
python -m pip install --upgrade pip
pip install setuptools wheel
pip install "crewai[tools]" google-auth google-auth-oauthlib google-api-python-client python-dotenv
```

### Verify Setuptools Installation

You can quickly verify that `setuptools` was installed correctly:

```bash
python -c "import setuptools; print(setuptools.__version__)"
```

## 4. Run Your Flow

With everything set up, you can now run your email auto-responder flow:

```bash
uv run kickoff
```
