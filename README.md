# ReactDocker - boilerplate for running React on Docker in Windows

### Development notes 
  * To run this code locally in docker development: 
  1. Open Docker Desktop 
  2. Open Ubuntu in WSL 
  3. Make sure Remote-WSL is installed in VS Code 
  4. Navigate to git repo in Ubuntu 
  5. run: 
  ```bash
  code . 
  ```
  6. Open Terminal in VS Code 
  7. In same dir as docker-compose.yml file, Run 
  ```bash 
   docker-compose up -d 
  ```
  8. React should be available on http://localhost:3000/
