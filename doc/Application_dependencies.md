# Application dependencies

## Dependencies for running online
Additional recommend environment dependencies:
```
- AWS S3 for hosting the frontend
- Elastic Beanstalk to install the backend for EC2
- CircleCI to automate it all
```

## For BE
```
"dependencies": {
    "@types/bcryptjs": "2.4.2",
    "@types/jsonwebtoken": "^8.3.2",
    "aws-sdk": "^2.429.0",
    "bcryptjs": "2.4.3",
    "body-parser": "^1.18.3",
    "cors": "^2.8.5",
    "dotenv": "^8.2.0",
    "express": "^4.16.4",
    "jsonwebtoken": "^8.5.1",
    "pg": "^8.7.1",
    "reflect-metadata": "^0.1.13",
    "sequelize": "^6.5.0",
    "sequelize-typescript": "^2.1.3"
  }
```

## For FE
```
  "dependencies": {
    "@angular/common": "^8.2.14",
    "@angular/core": "^8.2.14",
    "@angular/forms": "^8.2.14",
    "@angular/http": "^7.2.16",
    "@angular/platform-browser": "^8.2.14",
    "@angular/platform-browser-dynamic": "^8.2.14",
    "@angular/router": "^8.2.14",
    "@ionic-native/core": "^5.0.0",
    "@ionic-native/splash-screen": "^5.0.0",
    "@ionic-native/status-bar": "^5.0.0",
    "@ionic/angular": "^4.1.0",
    "core-js": "^2.5.4",
    "rxjs": "~6.5.4",
    "zone.js": "~0.9.1"
  },
```