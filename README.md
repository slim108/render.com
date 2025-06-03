/ (root)
  package.json
  backend/
    package.json
    ...
  frontend/
    package.json
    ...
  render.yaml
{
  "name": "pos-system",
  "version": "1.0.0",
  "description": "Point of Sale System",
  "scripts": {
    "start": "cd backend && npm start",
    "build": "cd frontend && npm run build",
    "install-all": "npm install && cd backend && npm install && cd ../frontend && npm install"
  },
  "engines": {
    "node": ">=14.0.0"
  }
}
