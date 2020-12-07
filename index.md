---
layout: default
title: Risk Management Framework for Information Systems and Organizations 
nav_order: 1
description: "Security and Privacy Controls for Information Systems and Organizations"
permalink: /
---

## NIST Special Publication 800-37

## Revision 2

# Risk Management Framework for Information Systems and Organizations
## A System Life Cycle Approach for Security and Privacy

**JOINT TASK FORCE**

This publication is available free of charge from:
[https://doi.org/10.6028/NIST.SP.800-37r2](https://doi.org/10.6028/NIST.SP.800-37r2)

**December 2018**

<div style="background-color:lightblue; padding:20px" markdown="1">
This publication contains comprehensive updates to the
Risk Management Framework. The updates include an
alignment with the constructs in the NIST Cybersecurity
Framework; the integration of privacy risk management
processes; an alignment with system life cycle security
engineering processes; and the incorporation of supply
chain risk management processes. Organizations can
use the frameworks and processes in a complementary
manner within the RMF to effectively manage security
and privacy risks to organizational operations and
assets, individuals, other organizations, and the Nation.
Revision 2 includes a set of organization-wide RMF tasks
that are designed to prepare information system owners
to conduct system-level risk management activities. The
intent is to increase the effectiveness, efficiency, and
cost-effectiveness of the RMF by establishing a closer
connection to the organization’s missions and business
functions and improving the communications among
senior leaders, managers, and operational personnel.
</div>

U.S. Department of Commerce
Wilbur L. Ross, Jr., Secretary

National Institute of Standards and Technology

_Walter Copan, NIST Director and Under Secretary of Commerce for Standards and Technology_

***

## Authority

This publication has been developed by NIST to further its statutory responsibilities under the
Federal Information Security Modernization Act (FISMA), 44 U.S.C. § 3551 et seq. , Public Law (P.L.) 113-283. NIST is responsible for developing information security standards and guidelines,
including minimum requirements for federal information systems, but such standards and
guidelines shall not apply to national security systems without the express approval of the
appropriate federal officials exercising policy authority over such systems. This guideline is
consistent with requirements of the Office of Management and Budget (OMB) Circular A-130.  

Nothing in this publication should be taken to contradict the standards and guidelines made
mandatory and binding on federal agencies by the Secretary of Commerce under statutory
authority. Nor should these guidelines be interpreted as altering or superseding the existing
authorities of the Secretary of Commerce, OMB Director, or any other federal official. This
publication may be used by nongovernmental organizations on a voluntary basis and is not
subject to copyright in the United States. Attribution would, however, be appreciated by NIST.  

National Institute of Standards and Technology Special Publication 800-53, Revision 5
Natl. Inst. Stand. Technol. Spec. Publ. 800-53, Rev. 5, 483 pages (September 2020 )

CODE N: NSPUE2

This publication is available free of charge from:
[https://doi.org/10.6028/NIST.SP.800-37r2](https://doi.org/10.6028/NIST.SP.800-37r2)

<div style="background-color:lightblue; padding:20px" markdown="1">
Certain commercial entities, equipment, or materials may be identified in this document to describe
an experimental procedure or concept adequately. Such identification is not intended to imply
recommendation or endorsement by NIST, nor is it intended to imply that the entities, materials, or
equipment are necessarily the best available for the purpose.<br><br>

There may be references in this publication to other publications currently under development by
NIST in accordance with its assigned statutory responsibilities. The information in this publication,
including concepts, practices, and methodologies, may be used by federal agencies even before the
completion of such companion publications. Thus, until each publication is completed, current
requirements, guidelines, and procedures, where they exist, remain operative. For planning and
transition purposes, federal agencies may wish to closely follow the development of these new
publications by NIST.  

Organizations are encouraged to review draft publications during the designated public comment
periods and provide feedback to NIST. Many NIST publications, other than the ones noted above,
are available at https://csrc.nist.gov/publications.
</div>

### Comments on this publication may be submitted to:
National Institute of Standards and Technology
Attn: Computer Security Division, Information Technology Laboratory
100 Bureau Drive (Mail Stop 8930) Gaithersburg, MD 20899-
Email: sec-cert@nist.gov

All comments are subject to release under the Freedom of Information Act (FOIA) [FOIA96].

***

## Reports on Computer Systems Technology

The National Institute of Standards and Technology (NIST) Information Technology Laboratory
(ITL) promotes the U.S. economy and public welfare by providing technical leadership for the
Nation’s measurement and standards infrastructure. ITL develops tests, test methods, reference
data, proof of concept implementations, and technical analyses to advance the development
and productive use of information technology (IT). ITL’s responsibilities include the development
of management, administrative, technical, and physical standards and guidelines for the cost-
effective security of other than national security-related information in federal information
systems. The Special Publication 800-series reports on ITL’s research, guidelines, and outreach
efforts in information systems security and privacy and its collaborative activities with industry,
government, and academic organizations.

## Abstract

This publication describes the Risk Management Framework (RMF) and provides guidelines for
applying the RMF to information systems and organizations. The RMF provides a disciplined,
structured, and flexible process for managing security and privacy risk that includes information
security categorization; control selection, implementation, and assessment; system and
common control authorizations; and continuous monitoring. The RMF includes activities to
prepare organizations to execute the framework at appropriate risk management levels. The
RMF also promotes near real-time risk management and ongoing information system and
common control authorization through the implementation of continuous monitoring
processes; provides senior leaders and executives with the necessary information to make
efficient, cost-effective, risk management decisions about the systems supporting their missions
and business functions; and incorporates security and privacy into the system development life
cycle. Executing the RMF tasks links essential risk management processes at the system level to
risk management processes at the organization level. In addition, it establishes responsibility
and accountability for the controls implemented within an organization’s information systems
and inherited by those systems.

## Keywords

assess; authorization to operate; authorization to use; authorizing official; categorize; common
control; common control authorization; common control provider; continuous monitoring;
control assessor; control baseline; cybersecurity framework profile; hybrid control; information
owner or steward; information security; monitor; ongoing authorization; plan of action and
milestones; privacy; privacy assessment report; privacy control; privacy plan; privacy risk; risk
assessment; risk executive function; risk management; risk management framework; security;
security assessment report; security control; security engineering; security plan; security risk;
senior agency information security officer; senior agency official for privacy; supply chain risk
management; system development life cycle; system owner; system privacy officer; system
security officer; system-specific control.

***

## Acknowledgements

This publication was developed by the Joint Task Force Interagency Working Group. The group
includes representatives from the Civil, Defense, and Intelligence Communities. The National
Institute of Standards and Technology wishes to acknowledge and thank the senior leaders from
the Departments of Commerce and Defense, the Office of the Director of National Intelligence,
the Committee on National Security Systems, and the members of the interagency working
group whose dedicated efforts contributed significantly to the publication.

### Department of Defense
Dana Deasy  
_Chief Information Officer_  

Essye B. Miller  
_Principal Deputy CIO and DoD Senior Information Security Officer_

Thomas P. Michelli  
_Acting Deputy Chief Information Officer for Cybersecurity_

Vicki Michetti  
_Director, Cybersecurity Policy, Strategy, International, and Defense Industrial Base Directorate_

### Office of the Director of National Intelligence
John Sherman  
_Chief Information Officer_

Vacant  
_Deputy Chief Information Officer_

Susan Dorr  
_Director, Cybersecurity Division and Chief Information Security Officer_

Wallace Coggins  
_Director, Security Coordination Center_

### National Institute of Standards and Technology
Charles H. Romine  
_Director, Information Technology Laboratory_

Donna Dodson  
_Cybersecurity Advisor, Information Technology Laboratory_

Matt Scholl  
_Chief, Computer Security Division_

Kevin Stine  
_Chief, Applied Cybersecurity Division_

Ron Ross  
_FISMA Implementation Project Leader_

### Committee on National Security Systems
Thomas Michelli  
_Chair—Defense Community_

Susan Dorr—Intelligence Community  
_Co-Chair_

Vicki Michetti  
_Tri-Chair—Defense Community_

Chris Johnson  
_Tri-Chair—Intelligence Community_

Paul Cunningham  
_Tri-Chair—Civil Agencies_

### Joint Task Force Working Group
Ron Ross  
_NIST, JTF Leader_

Taylor Roberts  
_OMB_

Jordan Burris  
_OMB_

Jeff Marron  
_NIST_

Dorian Pappas  
_CNSS_

Daniel Faigin  
_The Aerospace Corporation_

Kevin Dulany  
_DoD_

Ellen Nadeau  
_NIST_

Charles Cutshall  
_OMB_

Kaitlin Boeckl  
_NIST_

Dominic Cussatt  
_Veterans Affairs_

Christina Sames  
_The MITRE Corporation_

Peter Duspiva  
_Intelligence Community_

Victoria Pillitteri  
_NIST_

Kevin Herms  
_OMB_

Kirsten Moncada  
_OMB_

Esten Porter  
_The MITRE Corporation_

Julie Snyder  
_The MITRE Corporation_

Kelley Dempsey  
_NIST_

Naomi Lefkovitz  
_NIST_

Carol Bales  
_OMB_

Jon Boyens  
_NIST_

Celia Paulsen  
_NIST_

Martin Stanley  
_Homeland Security_

The authors also wish to recognize Matt Barrett, Kathleen Coupe, Jeff Eisensmith, Chris Enloe, Ned Goren, Matthew Halstead, Jody Jacobs, Ralph Jones, Martin Kihiko, Raquel Leone, and the scientists, engineers, and research staff from the Computer Security Division and the Applied Cybersecurity Division for their exceptional contributions in helping to improve the content of the publication. A special note of thanks to Jim Foti and the NIST web team for their outstanding administrative support.  

In addition, the authors wish to acknowledge the United States Air Force and the “RMF Next” initiative, facilitated by Air Force CyberWorx, that provided the inspiration for some of the new ideas in this update to the RMF. The working group, led by Lauren Knausenberger, Bill Bryant, and Venice Goodwine, included government and industry representatives Jake Ames, Chris Bailey, James Barnett, Steve Bogue, Wes Chiu, Kurt Danis, Shane Deichman; Joe Erskine, Terence Goodman, Jason Howe, Brandon Howell, Todd Jacobs, Peter Klabe, William Kramer, Bryon Kroger, Kevin LaSalle, Dinh Le, Noam Liran, Sam Miles, Michael Morrison, Raymond Tom Nagley, Wendy Nather, Jasmine Neal, Ryan Perry, Eugene Peterson, Lawrence Rampaul, Jessica Rheinschmidt, Greg Roman, Susanna Scarveles, Justin Schoenthal, Christian Sorenson, Stacy Studstill, Charles Wade, Shawn Whitney, David Wilcox, and Thomas Woodring.  

Finally, the authors also gratefully acknowledge the significant contributions from individuals and organizations in both the public and private sectors, nationally and internationally, whose thoughtful and constructive comments improved the overall quality, thoroughness, and usefulness of this publication.  

<div style="background-color:lightblue; padding:20px" markdown="1">
The authors acknowledge the many individuals who contributed to previous versions of Special Publication 800-37 since its inception in 2005. They include Marshall Abrams, William Barker, Beckie Koonge, Roger Caslow, John Gilligan, Peter Gouldmann, Richard Graubart, John Grimes, Gus Guissanie, Priscilla Guthrie, Jennifer Fabius, Cita Furlani, Richard Hale, Peggy Himes, William Hunteman, Arnold Johnson, Donald Jones, Stuart Katzke, Eustace King, Mark Morrison, Sherrill Nicely, Karen Quigg, George Rogers, Cheryl Roby, Gary Stoneburner, Marianne Swanson, Glenda Turner, and Peter Williams.
</div>

***
