# Catering Project

## Running

### Prerequisites

1. **Java**: Make sure Java is installed on your system and added to your PATH (Java 8 is recommended).
2. **Camunda BPM**: Download and install Camunda BPM for Windows ([Download link](https://camunda.org/release/camunda-bpm/wildfly11/7.9/camunda-bpm-wildfly11-7.9.0.zip)).

### Steps

1. **Start the Camunda server**:
   ```bash
   cd .\camunda-bpm-wildfly11-7.9.0
   start-camunda.bat

2. **Open the project in your IDE** and build it with Maven:
   - Select `Run As` -> `Maven install`.

3. **Login to Camunda**:
   - Go to [http://localhost:8080/camunda/app/tasklist/default/#/login](http://localhost:8080/camunda/app/tasklist/default/#/login).
   - Use the credentials:
     - **Username**: `demo`
     - **Password**: `demo`

4. **Start a new process**:
   - In the Camunda Tasklist, go to **Start process** -> **Catering**.