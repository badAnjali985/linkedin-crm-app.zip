{
  "builds": [{ "src": "package.json", "use": "@vercel/static-build" }],
  "routes": [{ "src": "/(.*)", "dest": "/" }]
}
