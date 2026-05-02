# WhatsApp Voice AI Agent

WhatsApp AI agent with voice transcription, FAQ handling, and appointment booking for aesthetic clinics.

## What it does

- Receives WhatsApp messages (text and audio)
- Transcribes voice messages using Groq Whisper
- Answers FAQs from a Google Sheets knowledge base
- Books, reschedules, and cancels appointments via Google Calendar
- Replies in any language via Meta Graph API

## Stack

- n8n (workflow automation)
- Groq (Whisper for transcription + LLaMA for AI responses)
- Meta WhatsApp Cloud API
- Google Calendar API
- Google Sheets (FAQ + CRM)

## Architecture

workflow.png

## Built by

AutoScale AI — AI automation agency for aesthetic and dental clinics.
