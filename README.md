# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Jade Dever Matthews

_Student NetID_: jcd7

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Stadium}
- Assumptions:
  - I assume that there is a limited budget specifically dedicated
    for security. I also will assume that the network is only accessible to
    the staff of the stadium rather than publically avaliable. Lastly, the 
    stadium also includes the parking lot around it.
- Assets:
  - The assests that are important include the two football teams, the
    audience, the statium staff. Other assests that should be secured include
    the two teams' equipment, the equipment of the staff, the money handled by
    staff, and all items sold at the stadium. The stadium/structural integrity
    is another important asset. Lastly, the internal network is
    something that needs to be secured; this network could involve electronic
    money transfer. 
- Threats:
  - There are two modes of threats: physical and virtual. The physical threats
    entail inflicting harm on the audience, staff, or other people in the
    stadium. This could be from a shooting, an explosive, an aggressive person,
    etc. Theft is another physical threat: theft of personal items, equipment,
    or other assets mentioned above. The virtual threats include eavesdropping 
    on packets sent accross the network and potentially comprimising the
    network.
- Countermeasures:
  - It would take a lot of man power to protect against a lot of physical
    threats to the point where the costs are unpracticle. For instance,
    protecting against a severe terrorist attack (like missles) is
    unreasonable. Protecting monetary transactions is important, but most
    likely there aren't a lot of highly classified materials being used. Thus,
    investing in higher levels of security than what is normally provided by
    the router is most likely not worth the cost.

## Problem 2
- Scenario: {Grading}
- Assumptions:
  - Confidentiallity between the grader and the student is not of concern (the
    grader is able to see who the name of the student affiliated with the
    assignemnt they are grading on). These assignments were submitted through
    canvas and thus inherit some of the built in security.
- Assets:
  - One of the primary assests that needs to be protected is the assignemnt and
    the grade of that assignemnt. The grader most likely has access to other
    assignments and thus, these are other assets that should be protected.
- Threats:
  - The main threat includes other students viewing the assignemnt(s) that are
    being graded. Also, since other graders most likely have access to the
    submissions, they could potentially leak the confidential information.
    Lastly, people outside of rice (including alumni) might be able to 
    get their hands on the student information.
- Countermeasures:
  - It might be important for all of the graders to have access to all of the
    submissions, thus, adding security to prevent another grader from leaking
    student information would cost usability thus making it impracticle for the
    situation.

## Problem 3
- Scenario: Your choice (User of Slate for entering in prospective student
  information)
- Assumptions:
  - As a user of Slate, I have no control over the security provided by slate
    iteself. Thus, and this may be inaccurate, I must put trust in the system
    that is being used to store confidential information.
- Assets:
  - The assets needing protection include confidential information stored for a 
    particular student including financial information, governmental
    information (i.e social security number), demographic information, test
    scores, and other information submitted for the application. Lastly, the
    other asset includes the user's account information and data on the
    computer.
- Threats:
  - One threat includes the compromising of a user's account thus giving them
    access to information they might not have been permitted to see.
    Adversaries could also attempt to steal student information or upload fake
    data (the adversary could upload false information or alter existing data 
    while pretending to be a prospective student).
- Countermeasures:
  - Most of the responsibilities for security lays in the hands of the
    developers of Slate. Although, it would be benefitial to secure the 
    computers themselves to prevent other avenues for malicous people to gain
    access to non-permitted content. Using bitlocker for encryption and using a
    good password for the computer are easy/low cost methods that could counter
    the threats. Lastly, enstilling good internet and computer usage principles
    is a must to ensure confidentiallity. Adding additional security messures,
    however, could compromise the usability of the users.

