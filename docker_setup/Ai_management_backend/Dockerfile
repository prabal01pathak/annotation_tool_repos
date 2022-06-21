FROM python:3.10
WORKDIR /app
COPY ./Ai_management_backend/pyproject.toml /app/
RUN pip3 install --upgrade pip
RUN pip3 install poetry
RUN poetry config virtualenvs.create false
RUN poetry install
COPY ./Ai_management_backend/ /app/
CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "8000"]
