# mcp-server-bluesky

MCP server for [Bluesky](https://bsky.app/).

## Usage with Claude Desktop

```json
{
  "mcpServers": {
    "bluesky": {
      "command": "npx",
      "args": ["-y", "mcp-server-bluesky"],
      "env": {
        "BLUESKY_USERNAME": "username",
        "BLUESKY_PASSWORD": "password",
      }
    }
  }
}
```

## Tools

- `bluesky_get_profile`
- `bluesky_get_follows`
- `bluesky_get_followers`
- `bluesky_post`
- `bluesky_get_timeline`
- `bluesky_get_post_thread`
- `bluesky_get_likes`
- `bluesky_like`
- `bluesky_delete_like`
