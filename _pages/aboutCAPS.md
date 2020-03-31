---
layout: page
title: About CAPS
include_in_header: true
---

# PROBLEM AND MOTIVATION
A sudden upsurge of 2019 novel coronavirus disease ( COVID-19 ) in Wuhan, China has rapidly turned into a nationwide pandemic affecting over 199 countries. As of now more than 65 Lakhs cases have been reported with over 30 thousand deceased and above 48 Lakhs of active cases [ <a href="https://www.worldometers.info/coronavirus/">source</a> ]. A mortality rate of 3.4% has been estimated by the World Health Organization [ <a href="https://www.who.int/dg/speeches/detail/who-director-general-s-opening-remarks-at-the-media-briefing-on-covid-19---3-march-2020">source</a> ]. According to the Ministry of Health and Socail Welfare, as of 28 March, the total number of cases in India has surpassed 900 with 19 reported deaths [ <a href="https://www.who.int/dg/speeches/detail/who-director-general-s-opening-remarks-at-the-media-briefing-on-covid-19---3-march-2020">source</a> ].Such appalling statistics have instilled motivation in our team to come up with something to tackle the outbreak and potentially break the chain of virus spread from one person to another. <a href="https://www.youtube.com/embed/BtN-goy9VOY">Kurzgesagt – In a Nutshell</a> gave an excellent demonstration in the video below about the novel Coronavirus and what should be done .

<iframe width="760" height="300" src="https://www.youtube.com/embed/BtN-goy9VOY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

 
<br>
When a person has tested COVID-19 positive, <img src="graph19.png" align="right" height="200" width="250">besides the treatment, an important task is to find out all the direct and indirect contacts of the patient for the previous 14 days. However, it is quite difficult for the person to name all such contacts direct contacts and is practically infeasible to identify the indirect contacts. Consequently, this might start a chain of COVID-19 spread.  To interrupt and break this chain, we developed CAPS, that is, COVID19 Affected People Surveillance App.   


# **FEATURES**
Through CAPS, users can record every person they have had contact with within a distance of 2 metres both directly or indirectly. This eventually leads the user to a graph of direct and indirect contacts. If any contact in the graph has tested COVID-19 positive , everyone else in the contact graph will be notified to act accordingly. In the current vulnerable circumstances, CAPS will help users to determine their own risk and thus, the importance of CAPS.
<br>

Let us explain the feature using an example, consider a person A and a person B, both having CAPS installed in their smartphones. Whenever they come in contact with each other, a new entry will be added in their respective CAPS app denoting that Person A has come in contact with Person B  along with time and location of contact and vice versa. The app creates an entry for all such contacts of CAPS users. Contact is detected between two users based on their GPS location and Bluetooth.
<br>

<img src="notification.png" height="300" width="1000">
Let's say Person A had contact with Person B  and Person B had contact with Person C. Now, if Person A has tested COVID-19 positive, his direct contact, that is, Person B and his indirect contact, that is, Person C will be notified immedietely. Moreover, every other user of CAPS will get this notification (as illustrated in figure above) so that they can avoid contact with them in future and hence, can potentially breaks the chain of virus spread. 
<br>

<img src="distance.jpg" height="250" width="740">


Finally, this app will also detect any public mass gathering nearby and its location and notify that to the user so that the user can avoid going to that location. Another use case of CAPS is that Police can detect such gathering and take appropriate actions to handle the gatherings. 

# **TECHINCAL DETAILS**



