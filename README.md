<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #474e5d;
  font-family: Helvetica, sans-serif;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: white;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #FF9F55;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}

/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .timeline::after {
  left: 31px;
  }
  
  /* Full-width containers */
  .container {
  width: 100%;
  padding-left: 70px;
  padding-right: 25px;
  }
  
  /* Make sure that all arrows are pointing leftwards */
  .container::before {
  left: 60px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
  }

  /* Make sure all circles are at the same spot */
  .left::after, .right::after {
  left: 15px;
  }
  
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
</style># Welcome to my profile
## About
<p align='center'>
    <a href="https://www.linkedin.com/in/ahashim/"><img height="30" src="https://github.com/WaylonWalker/WaylonWalker/blob/main/icon/linkedin.png?raw=true"></a>
</p>

## Career 
 <div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2004</h2>
      <p>Software Engineer, NTG Clarity</p>
      <details><summary>Projects</summary>
      <p>
        <li>Internet Service Provider Order Managemment</li>
        <li>Internet Service Provider Project Managemment</li>
        <li>Internet Service Provider Network Managemment</li>
        <li>Bandwidth On Demand "BoD" for Residential Subscribers</li>
      </p>
    </details>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2005</h2>
      <p>Software Developer, EDS</p>
      <details><summary>Projects</summary>
      <p>
        <li>UK Government, DWP, Job Centre Plus Portal</li>
        <li>UK Government, DWP, Job Warehouse  Portal</li>
      </p>
    </details>
    </div>
  </div>
    <div class="container left">
    <div class="content">
      <h2>2007</h2>
      <p>System Analyst, Etisalat Misr</p>
    </div>
  </div>
      <div class="container right">
    <div class="content">
      <h2>2009</h2>
      <p>Principal Consultant, Oracle</p>
      <details><summary>Projects</summary>
      <p>
        <li>Vodafone Qatar, Oracle ASAP</li>
        <li>Colt UK, VDC Provisioning using Oracle OSM</li>
        <li>Colt UK, MetroEthernet Services Provisioning using Oracle OSM</li>
        <li>Vodacom South Africa, VoIP Service Provisioning using Oracle OSM</li>
      </p>
    </details>
    </div>
    <div class="content">
      <h2>2012</h2>
      <p>Senior Principal Consultant, Oracle</p>
      <p>OSS Solution Architect</p>
      <details><summary>Projects</summary>
      <p>
        <li>MTS Russia, Triple-Play services Provisioning using Oracle Siebel and OSM</li>
      </p>
    </details>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2016</h2>
      <p>Software Architect, Cisco</p>
    </div>
    <div class="content">
      <h2>2021</h2>
      <p>Senior Software Architect, Cisco</p>
    </div>
  </div>
</div> 


## Projects
## Roles and Responsbilities
- Solution Architect
- Pre-Sales Architect
- Technical Product Manager
- Business Development Manager

## Certifications
<p align='center'>
    <a href="https://www.youracclaim.com/badges/6f0a978c-bf15-4573-ac52-ca86132e8cf5/public_url"><img height="80" src="https://images.youracclaim.com/size/680x680/images/f0adcc07-4388-459f-9b98-9a487ff1e8fd/cert_mark_SP_badge_large_300px.png"/></a>
    <a href="https://www.youracclaim.com/badges/8cbe55cb-ece8-4807-8be2-ef71f08fe513/public_url">
        <img height="80" src="https://images.youracclaim.com/size/680x680/images/4bc21d8b-4afe-4fbd-9a90-a9de8bf7b240/AWS-SolArchitect-Associate-2020.png"/>
    </a>
    <a href="https://www.youracclaim.com/badges/a26037a3-9239-4942-92ab-e42c481f8679/public_url"><img height="80" src="https://images.youracclaim.com/size/680x680/images/86d57ae1-0e9c-4776-80cf-d922facef690/CiscoDevNet500.png"/></a>
    <a href="https://www.youracclaim.com/badges/38833e20-1bc7-4434-89a4-aa8d7aba7876/public_url"><img height="80" src="https://images.youracclaim.com/size/680x680/images/21e9b68d-c6d1-4e87-8053-fae7a3fdcb2d/Cisco_DevNetSpecialist.png"/></a>
    <a href=""><img height="80" src="https://www.scrumalliance.org/ScrumRedesignDEVSite/media/badge-library/SAI_BadgeSizes_DigitalBadging_CSM.png"/></a>
    <a href=""><img height="80" src="https://www.tmforum.org/wp-content/uploads/2020/06/BDM-badge.png"/></a>
    <a href=""><img height="80" src="https://www.tmforum.org/wp-content/uploads/2020/06/BPM-Badge.png"/></a>
    <a href=""><img height="80" src=""/></a>
</p>

# Online Resources for Computer Science Students
## PluralSight
PluralsightOne offers free content to students, this is very organized and high quality training courses. To register visit this [link](https://www.pluralsightone.org/product/education/code-org-redemption-3m). Once you have your account activated, you will get access to aprox. 1,000 hours of training course. I am listing below some courses I recommmend.

### GoLang
- [Go: The Big Picture](https://app.pluralsight.com/library/courses/go-big-picture/table-of-contents)
- [The Go CLI Playbook](https://app.pluralsight.com/library/courses/go-cli-playbook/table-of-contents)
### Python
- [Python for Data Analysts](https://app.pluralsight.com/library/courses/python-data-analysts/table-of-contents)
- [Importing Data: Python Data Playbook](https://app.pluralsight.com/library/courses/python-importing-data-playbook/table-of-contents)
- [Business Automation with Python: Getting Started](https://app.pluralsight.com/library/courses/business-automation-python-getting-started/table-of-contents)
- [Understanding Machine Learning with Python](https://app.pluralsight.com/library/courses/python-understanding-machine-learning/table-of-contents)
- [Python: The Big Picture](https://app.pluralsight.com/library/courses/python-big-picture/table-of-contents)
### DevOps
- [Docker Deep Dive](https://app.pluralsight.com/library/courses/docker-deep-dive-update/table-of-contents)
- [Docker Swarm: Native Docker Clustering](https://app.pluralsight.com/library/courses/docker-swarm-native-docker-clustering/table-of-contents)
- [Computer Fundamentals: Operating Systems](https://app.pluralsight.com/library/courses/computer-fundamentals-operating-systems/table-of-contents)
### Database
- [Querying Data from PostgreSQL](https://app.pluralsight.com/library/courses/querying-data-postgresql/table-of-contents)
### Web Development
- [React: Getting Started](https://app.pluralsight.com/library/courses/react-js-getting-started/table-of-contents)
## Hashim Grant
If you are from Egypt and you want to study any computer science courses online but can't afford the course fees, send an email to hashim+grant{[at]}egjug.org with the course URL, your student id.

## Contact
hashim{[at]}egjug.org