# Thinkboi

A collection of Claude skills designed to transform raw notes into clear, structured thoughts suitable for professional social media platforms like LinkedIn.

## Overview

Thinkboi helps bridge the gap between initial ideas captured in voice notes and polished, well-articulated content. The skills focus on thought clarification through an interactive process—asking targeted follow-up questions to help refine and structure your thinking.

## The Musings Page

The workflow centers around a Notion page called "Musings"—a place to capture whatever is top of mind. The process is simple: hit voice record, talk through something that got you thinking, and let the transcription land in Notion. These raw thoughts might be interesting to share with others, but they need structure and clarity first. That's where Thinkboi comes in.

The Musings page is intentionally unfiltered. It contains the rough, unpolished seeds of ideas. Thinkboi's job is to help develop those seeds into something coherent enough to share.

## How It Works

1. **Capture**: Record thoughts using voice-to-text (Wispr Flow) into your Musings page in Notion
2. **Connect**: Thinkboi reads from the Musings page via the Notion MCP integration
3. **Clarify**: The skills analyze your notes and ask follow-up questions to surface underlying insights
4. **Structure**: Transform clarified thoughts into coherent, professional content

## Features

- **Notion Integration**: Connects to your Notion workspace via MCP to read source notes
- **Interactive Clarification**: Asks thoughtful follow-up questions rather than making assumptions
- **Professional Output**: Structures content appropriately for LinkedIn and other professional platforms

## Requirements

- Claude with skills support
- Notion MCP server configured
- A Notion page for capturing raw notes (default: "Musings")

## Setup

1. Configure the Notion MCP server with access to your workspace
2. Ensure your notes page is accessible to the MCP integration
3. Load the Thinkboi skills into your Claude environment

## Usage

Once configured, share your raw notes or reference your Notion page, and Thinkboi will guide you through the clarification process with targeted questions before helping structure your thoughts for publication.

## Development

This project is developed entirely using Claude Code on mobile with voice input via Wispr Flow—an experiment in voice-driven development without traditional keyboard interaction.

## License

MIT
