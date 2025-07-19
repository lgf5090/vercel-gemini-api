
# Gemini API Proxy
vercel-gemini-api

A simple proxy service for gemini API using Vercel Edge Functions.

## Features

- ✅ Edge runtime for better performance
- ✅ Automatic request forwarding
- ✅ CORS support
- ✅ Error handling

## Usage

After deployment, replace `api.gemini.com` with your Vercel domain:

```bash
# Original
curl https://api.gemini.com/v1/models

# Through proxy
curl https://your-proxy.vercel.app/v1/models

