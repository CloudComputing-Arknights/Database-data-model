
VM Info:
	- Microservice 1 (Cloud Run)
		URL: https://users-api-121084561869.us-central1.run.app
		JWT-SECRET: ruvYP5J6JMxTQXDmUMlmFno15AHLe4QgbYu49UmTG4w/g2k5lp+eG2W2TAqN1j4D
		GOOGLE_CLIENT_ID: 121084561869-4shc71k483dm5un915qp0hd719l152b7.apps.googleusercontent.com
Cloud SQL: 
			IP : 136.116.185.109
			username: users_svc
password: MicroService1-users
database: users_db

	Microservice 2 (Cloud Run)
		URL: https://microservice-item-848539791549.us-central1.run.app
		Cloud SQL: 
			IP: 34.121.148.86
			Username: root
			Password: Arknights123!
			Database: neighborhood-item-db
Microservice 3 (VM)
		IP: http://34.172.7.104:8000
	MySQL (VM)
		IP: 136.113.127.151
username: microservice_3
password: arknights123
database: neighborhood_db
	Microservice 4 (Cloud Run)
		URL: https://messaging-ms-183134360923.us-central1.run.app/ 
		Cloud SQL:
			IP: 34.57.117.148
			Username: app_user
		Password: messagingDB
		Database: messaging_db
	Composite Microservice (Cloud Run)
		URL: https://composite-microservice-191058157831.us-west2.run.app
		MySQL (Cloud SQL)
			IP: 34.94.204.21
			username: composite
			password: Arknights_123
			database: composite
	Web UI (Cloud Storage)
		URL: https://cloud-computing-web-ui-app.storage.googleapis.com/index.html
	Web UI (Cloud Run)
URL: https://browser-web-application-177030329297.europe-west1.run.app/ 
