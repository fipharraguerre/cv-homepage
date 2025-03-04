---
layout: default
title: "My CV - English Version"
lang: "en"
permalink: /en/

sidebar: |
  ## Facundo Ipharraguerre
  
  ### Profile Summary 
  - Telecommunications Engineer with expertise in IT infrastructure and software development. 15+ years in Linux, Windows Server, cloud, networking, and automation. Skilled in security, agile methodologies, and virtualization. Experience working under an ISO 9001 quality management system. Fluent in Spanish (native) and conversational English.
  - Location: Córdoba, Argentina
  
<style>
  .collapsible {
    cursor: pointer;
    padding: 10px;
    border: 1px solid #ccc;
    background-color: #f8f8f8;
    text-align: left;
    font-weight: bold;
    user-select: none;
    margin-top: 10px;
  }
  
  .content {
    display: none;
    padding: 10px;
    border-left: 3px solid #ddd;
    margin-bottom: 10px;
  }
</style>

  ### Skills
  A combination of infrastructure, automation, and development expertise, spanning networking, virtualization, scripting, databases, monitoring, and software methodologies.

<div class="collapsible" aria-expanded="false">Click to expand</div>
<div class="content">
  <ul>
    <li><strong>Infrastructure & Networking</strong>
      <ul>
        <li>Network administration, Windows Server (Active Directory, Entra ID), Linux, and Veeam Backup & Replication.</li>
      </ul>
    </li>
    <li><strong>Virtualization & Containers</strong>
      <ul>
        <li>Expertise in VMware ESX, Hyper-V, Proxmox (KVM), Docker (including Swarm), and Linux Containers (LXC) for scalable and flexible deployments.</li>
      </ul>
    </li>
    <li><strong>Programming & Scripting</strong>
      <ul>
        <li>Proficient in Python (automation, data analysis, web apps), Bash, PowerShell, and C for embedded systems.</li>
      </ul>
    </li>
    <li><strong>Databases & Web Technologies</strong>
      <ul>
        <li>Experience with SQL Server, MySQL, MariaDB, MongoDB, Redis, SQLite, and backend development with web servers.</li>
      </ul>
    </li>
    <li><strong>Monitoring & Reporting</strong>
      <ul>
        <li>Building dashboards with Grafana and processing data using Excel for reporting and analytics.</li>
      </ul>
    </li>
    <li><strong>Methodologies & Soft Skills</strong>
      <ul>
        <li>Agile (SCRUM), strong problem-solving, and fluency in Spanish (native) and English (professional/conversational).</li>
      </ul>
    </li>
  </ul>
</div>

<script>
  document.querySelectorAll(".collapsible").forEach(button => {
    button.addEventListener("click", function() {
      var content = this.nextElementSibling;
      var isOpen = content.style.display === "block";

      // Toggle visibility
      content.style.display = isOpen ? "none" : "block";
      this.setAttribute("aria-expanded", !isOpen);
    });
  });
</script>

---

### Experience
{% include experience_en.md %}

---

### Education
{% include education_en.md %}

---

### Projects
{% include projects_en.md %}
