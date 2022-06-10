# A proposed method for decentralized  community-driven peer review


## GAP STATEMENT and TASK AT HAND
 Journal based peer review is inequitable, inefficient, and generally a steaming pile of hot garbage
	- e.g. dan goodman blog post
	
However, peer review currently plays an essential role in the vehicle of scientific progress and human inquiry, so it cannot be rejected wholesale *without a viable alternative.*

Hence, **we must create an alternative form of community based review** that serves the same role as the current system of journal-based peer review, while also being:
	- an equal-or-superior method of scientific pre-evaluation and consensus of technical soundness of a given manuscript
	- Better suited to modern world and imminent concerns relating to current structural inequities and potential future cataclysms 
	- Equitable and decentralized
	- Managed "as autonomously as possible" with individual human and community  in-the-loop oversight to mitigate unavoidable algorithmic bias and bad-actor trolling


## What is the role of peer review?
Peer review is used to determine whether a given work could constitute a **non-zero net positive** or a **net negative** if entered into [[Web of Knowledge]] - a **Quinian web-of-belief** epistemological structure comprising the total of human knowledge

Some of the practical functions of peer-review:
	- **Pre-verification by domain experts** so people know they can 'trust' a given piece of work 
		- protection from low-quality, unreliable effort
		- maintain integretiy of scientific web of knowledge/belief
		- Allows non-domain-experts to safely ingest the new knowledge without needing to develop the domain-expertise to determine validity of a given contribution
		- 
	- **It tells us what we are allowed to cite**
		- New contributions must connect to the broader context of inquiry by citing other people's work 
		- The current system of peer review provides an easy mechanism to determine 'validity' of a given publication
			- i.e. if it's published in a journal, it is assumed to be 'trustworthy' to the effect that citing it will not diminish the epistemolgical validity of your work
			-
	- **It provides a record of an individual's contributions**
		- A person's citation record is presumed to show the number of direct contributions that person has provided to the [[Web of Knowledge]]
			- This is beneficial both to 
				- the person (as they can and should benefit from communal trust derived with previous contributions)
				- the community (as it allows us to determine the trustworthiness of individuals with whom we have had no previous or direct contact)

## "Definition of Done"
The first phase of this project aims to create a viable alternative to the current system of journal-mediated peer review

In the abstract, we will have created a viable alternative to journal based peer review when the community of scientists views/treats papers evaluated through Community Review in a manner similar to papers published through traditional peer review

More concretely, I figure we'll have successfully created a viable alternative to traditional peer review **when papers that have recieved Community Review are eligible for a PubMedID (PMID)** 

## PROPOSED COMMUNAL PEER REVIEW PROCESS 
- (For simplicity, we will assume journal-paper-like contributions)
- Long story short, imagine a message board combined with `git`- like version tracking where:
	- Members can comment on specific parts of the paper or on the paper as a whole
	- comments recieve 'votes' from community members (similar to the 'upvote/downvote' system in Reddit)
		- votes from #vetted  community members carry greater weight than #non-vetted 
		- There will also probably need to be some sort of score whereby #vetted members with more relevant background are weighted more heavily (perhaps again via the #NeuroMatch inspired #matching algorithm?)
- The review process may someday be full-automoated and organic, but may require assignment to relevant #vetted community members to act as #Facilitator for a given review (similar to the job of an Editor in a traditional peer-review system)
	- with #matching system analogous to the one developed by/for #NeuroMatch
	- a "volunteer/dibs" system similar to the various methods used by larger #open-source projects
	
### 1 - Initial submission
- Pre-prints submitted to some kind of **public** form where it can be seen/read/commented on by  #vetted and #non-vetted community members.
	- [[Vetting community memebers]]
- New submissions are tagged as #Fresh 🌱 and #NoConsensus (yellow question mark ~->❔)
	- #Fresh papers are automatically entered into the [[New Submission pool]] , wherein both #vetted and #non-vetted members provide a [[superficial review]]
	- Papers that pass this  superficial review are then assigned an #UnderCommunityReview tag

### 2 - Community evaluation
A. Community members are encouraged and provided financial #incentive to actively participate, evaluate, and critique incoming research.
	- [[Incentive structure]]
	a. Evaluation by  #vetted members is weighted higher than #non-vetted members
		- and scaled by that #NeuroMatch inspired #matching algorithm
			
### 3 - Review Outcomes
Once a paper reaches `some critical level` of [[communal consensus]], it loses the #NoConsensus and #UnderCommunityReview tags  and may receive one of the following tags:
 - #CommunityAccepted (Green Check Mark -> ✔)
	 -  This paper is of sufficient quality and technical-soundness that it has been determined that it is considered to be a **non-zero net-positive** contribution to [[Web of Knowledge]] 
 -  #CommunityRejected (Red X -> ❌)
	 - If a paper is found to be technically unsound, misleading, or it is otherwise determined that it would be be a **net-negative** to include in [[Web of Knowledge]]
		 - Rejected papers may additionally have the #RevisionRequested (💫)tag applied
		 - Rejected papers may be resubmitted *ad nauseum* but they will not enter into the [[Active review match making service]]
	 
 NOTE - Rolling evaluation process 
	 - No time out or expiration
		- Papers that never reach ✔status remain a part of the record while maintaining the #NoConsensus tag
		- Papers that do not reach **Green** within 6-months lose the #UnderCommunityReview are marked #Stale (empty hourglass ->⏳) if there is no active discussion)
			- Papers have #Stale  status removed when new discussion emerges on their submission
			
## Citation Viability 
The following tags (or combinations of tags) are considered #citeable (i.e. a paper may cite this paper while maintiaining its #CommunityAccepted status:
	 - #CommunityAccepted 
	 - #NoConsensus + #Fresh
		 - i.e. you are allowed to cite freshly submitted papers, but if that paper is later rejected you'll need to revise your paper to exclude the citation 
	 - #NoConsensus + #RevisionRequested 
	 - Also, any paper published through traditional peer review
- The following tags (or combinations of tags) are considered #non-citeable. A paper that cites a #non-citable paper Is automatically downgraded to #NoConsensus until the paper has been satisfactorily altered to remove the unacceptable citation (if possible). 
	- #CommunityRejected
	- #NoConsensus + #Stale 
		- i.e. if a paper never reaches consensus, it is not viable for citation