# AI-That-Detects-Hallucination-In-LLM-Response
AI-That-Detects-Hallucination-In-LLM-Response 

An open-source framework and automated evaluation system designed to detect, score, and flag hallucinations in Large Language Model (LLM) outputs in real time.

This repository implements multi-layered evaluation techniques—including "Context Groundedness (RAG Faithfulness), LLM-as-a-Judge, Self-Consistency Analysis (Semantic Entropy), and Token-Level Uncertainty Estimation"—to ensure AI applications deliver accurate, reliable, and verifiable responses.



Features

- RAG Faithfulness & Groundedness Checking: Evaluates whether the generated LLM response is strictly backed by the retrieved source context.
- LLM-as-a-Judge Evaluation: Uses specialized evaluator models (or prompts) to audit generated responses and classify them as `factual` or `hallucinated`.
