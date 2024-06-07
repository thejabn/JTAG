<!DOCTYPE html>
<html lang=\"en\">
<head>
<meta charset=\"UTF-8\">
<meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">
<title>Dynamically Print Date and Time</title>
</head>
<body>
<h1>Current Date and Time</h1><p id="datetime"></p><script>
    function updateDateTime() {
		debugger;
      var currentDate = new Date();
	  console.log(currentDate);
      var datetimeElement = document.getElementById('datetime');
      datetimeElement.textContent = 'Current Date and Time: ' + currentDate;
    }

    // Update date and time every second
    setInterval(updateDateTime, 1000);
  </script>
  </body>
  </html>
### Pull Request (PR) Template Checklist Details

1. **Which environment we need to deploy?**
   - [ ] Development
     - [ ] Dev0
     - [ ] Dev1
     - [ ] Dev2
     - [ ] Dev3
     - [ ] Dev4
   - [ ] QA
     - [ ] QA0
     - [ ] QA1
     - [ ] QA2
   - [ ] Pre-production
     - [ ] Pre-prod0
     - [ ] Pre-prod1
     - [ ] Pre-prod2
   - [ ] Production

2. **What is the JIRA number?**
   - JIRA Number & Title: [Add JIRA Number Here]

3. **Brief description about feature\/bug fix?**
   [Add description here]
   
4. **Reference PR's (If any)**
   [Add links here]
