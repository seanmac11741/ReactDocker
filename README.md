# carlosPodcast

### Todos 
- [ ] Add mongo db docker container 
- [ ] Add express container 
- [ ] Create basic crud operations 
- [ ] Make basic tests 
- [ ] Make static react website that looks halfway decent 
- [ ] Deploy to production AWS manually 
- [ ] Setup automated testing and CI/CD 


## Final product design 
  * React front-end 
  * Express API 
  * Mongo DB backend 
  * all dockerized
  * deployed on AWS 
  * full CI/CD with Jenkins 
  * Full test suite 

## Final product features 
  * Website with a list of podcasts. Links to youtube, spotify, apple, etc 
  * Admin page for updating and adding new entries for new episodes 
  * Embedded Youtube links so you can watch videos in real time on the site 
  * Paid tier with more videos 
  * All videos (just the links) will be stored on a mongo DB in the backend 
  * React front-end will build a list of video entries from DB and make scrolling list 
  * Utilizing rest calls to DB entries of each episode 

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
