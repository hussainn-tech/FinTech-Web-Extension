{
  "manifest_version": 3,
  "name": "Investment Advisor",
  "description": "Get AI-generated investment advice every 10 seconds",
  "version": "1.0.0",
  "icons": {
    "128": "icons/icon.png"
  },
  "action": {
    "default_icon": {
      "32": "icons/icon.png"
    },
    "default_popup": "index.html",
    "default_title": "Open Popup"
  },
  "permissions": [
    "storage"
  ],
  "host_permissions": [
    "https://api.openai.com/"
  ]
}
