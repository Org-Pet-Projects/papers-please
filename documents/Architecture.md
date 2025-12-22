## Keycloak Setup (Authentication)

This application uses Keycloak for authentication and authorization.

### 1. Install Keycloak
- Download Keycloak from [https://www.keycloak.org/](https://www.keycloak.org/)
- Unpack and run the server:
```bash
bin/kc.sh start-dev
````

### 2. Create Realm and Client

1. Open Keycloak Admin Console (`http://localhost:8080/`)
2. Create a new **Realm** for the application
3. Create a new **Client** inside the realm

   * Client Protocol: `openid-connect`
   * Access Type: `confidential` (if using backend credentials)

### 3. Configure Application

* Add Keycloak configuration to `application.yml` or `application.properties`:

```yaml
keycloak:
  realm: YourRealmName
  auth-server-url: http://localhost:8080/
  resource: YourClientName
  credentials:
    secret: <client-secret>
```

### 4. Running the Application

* Start Spring Boot:

```bash
mvn spring-boot:run
```

* The application should now redirect login requests to Keycloak.

### 5. Notes

* Make sure the Keycloak server is running before starting the application.
* Add any roles or user mappings needed for your workflows.

```
