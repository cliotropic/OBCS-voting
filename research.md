# Blockchain voting background

This is a bibliography and collection of notes on the use of blockchain for voting systems. It's intended to provide an introduction to the challenges of voting security and reliability, not all of which are solvable with blockchain.

## West Virginia 2018 fall elections to use Voatz blockchain smartphone voting system
* https://www.technologyreview.com/s/611850/why-security-experts-hate-that-blockchain-voting-will-be-used-in-the-midterm-elections/
  * "The [Voatz] system isn’t so much a blockchain-based app as it is a mobile app with a blockchain attached, says Marian K. Schneider, president of Verified Voting. The blockchain can’t protect the information as it travels over the internet, and doesn’t guarantee that a user’s choices will be reflected accurately. “I think they’ve made a lot of claims that really don’t justify any increased confidence in what they are doing versus any other internet voting system,” Schneider says."
* http://www.govtech.com/data/GT-OctoberNovember-Securing-the-Vote.html
  * "“My recommendation,” said Ron Rivest, a computer science professor at the Massachusetts Institute of Technology for more than four decades, “is to have all voting be done on paper.”"
  * "Voatz isn’t the only company working on this. There’s Follow My Vote, a Virginia-based company with its own blockchain-based platform. Then there’s Blockchain Technologies Corp. in New York, and E-Vox in Kiev, Ukraine."
  * "Rivest and Benaloh both talk about another online voting solution with much more enthusiasm. And much in the spirit of academia, the technology’s name is pragmatic rather than sleek and buzzworthy: end-to-end verifiable Internet voting (E2E-VIV). It’s not too far off from blockchain in spirit, but it relies on a centralized approach instead of a decentralized one. Votes are sent from remote electronic devices to the election authority, most likely the secretary of state for the state the person is voting in, and posted online in an encrypted format. The person voting can use her decryption key to check that her vote was recorded accurately."
* https://www.bloomberg.com/news/articles/2018-08-10/is-blockchain-technology-the-future-of-voting
  * "Skeptics say blockchain voting won’t improve security. It’s “mostly hype,” says J. Alex Halderman, a University of Michigan computer science professor known for hacking into voting machines. He says there are still core security problems with mobile voting that blockchain doesn’t solve, such as preserving anonymity and transferring votes from smartphones infected with malware. It’s “worthy of research and study—but it may be decades until we get there,” Halderman says."
  * "These mobile systems also lack a paper backup, making it hard to audit vote counts, according to Audrey Malagon, a mathematics professor working with the advocacy group Verified Voting Foundation. “I hope they recognize that this isn’t ready for widespread use,” she says."
* https://www.wired.com/story/smartphone-voting-is-happening-west-virginia/
  * ""Because of current technological limitations, and the unique challenges of running public elections, it is impossible to maintain separation of voters’ identities from their votes when Internet voting is used," concludes a 2016 joint report from Common Cause, Verified Voting, and the Electronic Privacy Information Center. That's true whether those votes were logged by email, fax, or an online portal."


## Background on Voatz & its solution

* https://blog.voatz.com/?p=454
  * Uses Hyperledger, running on AWS and Azure
* https://www.bloomberg.com/news/articles/2018-08-10/is-blockchain-technology-the-future-of-voting
  * "The [WV elections] pilot program was funded with a $150,000 grant from Tusk/Montgomery Philanthropies Inc., a foundation set up by venture capitalist and former Uber Technologies Inc. adviser Bradley Tusk. When he heard about Warner’s interest, he asked one of his teams to research mobile voting startups. For the pilot, they picked Boston-based Voatz Inc. Tusk’s broader aim is to expand voter participation in the U.S. by enabling more mobile voting. "
* https://www.wired.com/story/smartphone-voting-is-happening-west-virginia/
  * "The biometrics part occurs when a voter authenticates their identity using a fingerprint scan on their phones. The app works only on certain Androids and recent iPhones with that feature. Voters must also upload a photo of an official ID—which Sawhney says Voatz verifies by scanning their barcodes—and a video selfie, which Voatz will match to the ID using facial-recognition technology. (“You have to move your face and blink your eyes to make sure you are not taking a video of somebody else or taking a picture of a picture,” Sawhney says.) It’s up to election officials to decide whether a voter should have to upload a new selfie or fingerprint scan each time they access the app or just the first time."
* [Smartphone Voting: Impossible or Inevitable?](https://www.nass.org/sites/default/files/2018-02/clear-ballot-voatz-white-paper-nass-winter18_4.pdf), white paper by Clear Ballot and Voatz.


## Technical background on Follow My Vote:

* https://followmyvote.com/blockchain-voting-the-end-to-end-process/
* https://followmyvote.com/online-voting-technology/blockchain-technology/


## On security and blockchain:

* https://www.technologyreview.com/s/610836/how-secure-is-blockchain-really/
* Matt Blaze, election security expert, on WV blockchain voting plan: https://twitter.com/mattblaze/status/1002921011854143488
* J. Alex Halderman, ECS, UMichigan: https://jhalderm.com/
  * [Securing Digital Democracy](https://www.coursera.org/learn/digital-democracy), Coursera MOOC
* "Actually, one of the biggest concerns about E2E-VIV is one that would also apply to blockchain, or any other online voting system: denial of service attacks." http://www.govtech.com/data/GT-OctoberNovember-Securing-the-Vote.html
* "“In my opinion, anybody purporting to have securely and robustly applied blockchain technology to voting should have prepared a detailed analysis of how their system would respond to a long list of known threats that voting systems must respond to, and should have made their analysis public,” Carnegie Mellon computer scientist David Eckhardt wrote in an email."
  * https://www.wired.com/story/smartphone-voting-is-happening-west-virginia/

## Academic research on e-voting (blockchain and otherwise):

* [E-VOTE-ID, The International Conference for Electronic Voting](https://www.e-vote-id.org/)
* Bernhard et al., "[Public Evidence from Secret Ballots,](https://arxiv.org/abs/1707.08619)" _Proc. 2nd International Joint Conference on Electronic Voting (E-Vote-ID ’17),_ October 2017
  * For the full list of papers from this conference, see https://link.springer.com/book/10.1007/978-3-319-68687-5 .
* [E2E-VIV Project: End-to-End Verifiable Internet Voting](https://www.usvotefoundation.org/E2E-VIV)
