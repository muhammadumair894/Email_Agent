# Email_Agent

Navigate to your project directory
cd D:\Agents\crewAI-examples\email_auto_responder_flow

Create a new virtual environment:
python -m venv .venv

Activate the new environment:
.\.venv\Scripts\activate

Install all required packages in the correct environment:
python -m pip install --upgrade pip
pip install setuptools wheel
pip install "crewai[tools]" google-auth google-auth-oauthlib google-api-python-client python-dotenv

Verify the installation:
python -c "import setuptools; print(setuptools.__version__)"

 running your flow
 uv run kickoff
