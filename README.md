# Thinkboi

A collection of Claude skills that transform raw voice notes into clear, structured thoughts for LinkedIn and other professional platforms.

## The Musings Page

The workflow centers around a Notion page called "Musings." Hit voice record, talk through something that got you thinking, and let the transcription land in Notion. These raw thoughts might be interesting to share with others, but they need structure and clarity first. That's where Thinkboi comes in.

The Musings page is intentionally unfiltered. It contains rough, unpolished seeds of ideas. Thinkboi helps develop those seeds into something coherent enough to share.

## How It Works

1. **Capture**: Record thoughts using voice-to-text (Wispr Flow) into your Musings page in Notion
2. **Connect**: Thinkboi reads from the Musings page via the Notion MCP integration
3. **Clarify**: The agent prompts you with questions to work through your ideas. Answer via voice or text, going back and forth until things are clear and presentable for a professional audience
4. **Structure**: Transform clarified thoughts into coherent, professional content

## Requirements

- Claude with skills support
- Notion MCP server configured with access to your Musings page

## Development

This project is developed mostly using Wispr Flow on mobile, with a little bit of Wispr Flow on desktop via Cursor.

## License

MIT
