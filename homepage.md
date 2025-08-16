---
cssclasses:
  - four-column-list
---
### published
```dataviewjs
const pages = dv.pages("").where(p => p.file.path.includes("content/") && (p.draft === false) ); const grouped = pages.groupBy(p => p.file.folder); for (let group of grouped) { dv.header(6, group.key); dv.list(group.rows.map(p => p.file.link)); 
}
```
### unpublished
```dataviewjs
const pages = dv.pages("").where(p => p.file.path.includes("content/") && (p.draft === true || p.draft === undefined || p.draft === null) ); const grouped = pages.groupBy(p => p.file.folder); for (let group of grouped) { dv.header(6, group.key); dv.list(group.rows.map(p => p.file.link)); 
}
```

### writing prompts

1. Pretend everybody was sent to you to teach you something.
2. Your career is a story that you can sell. You can craft all of your experiences and skills around different narratives depending on what you want to do that
3. Basically, manage your calendar. Block out time that is optimal for you to do certain things. People will learn over time to respect your time blocks.
4. Opinions of others are useful for understanding different perspectives. But they don't have to influence yours.
5. Doing lots of different things in your career can make you well rounded and lead to greater success than climbing a linear path.
6. You never know when you will need the support and backing of others. Give it others, esp those early in their career.
7. Don't overthink or over analyse. Do the thing if it interests you. Do it because you want to!
8. Be brave. Even if you’re not, pretend to be. No one can tell the difference.
9. Lend only those books you never care to see again.
10. When playing games with children, let them win.
11. Give people a second chance, but not a third.
12. Become the most positive and enthusiastic person you know.
13. Loosen up. Relax. Except for rare life-and-death matters, nothing is as important as it first seems.
14. Don’t allow the phone to interrupt important moments. It’s there for our convenience, not the caller’s.
15. Think twice before burdening a friend with a secret.
16. When someone hugs you, let them be the first to let go.
17. Keep it simple.
18. Beware of the person who has nothing to lose.
19. Don’t burn bridges. You’ll be surprised how many times you have to cross the same river. Except the bridges that lead you to hell.
20. Take charge of your attitude. Don’t let someone else choose it for you.
21. Visit friends and relatives when they are in the hospital; you only need to stay a few minutes.
22. Begin each day with some of your favourite music.
23. Once in a while, take the scenic route.
24. Answer the phone with enthusiasm and energy in your voice.
25. Keep a notepad and pencil on your bedside table. Million-dollar ideas sometimes strike at 3 a.m.
26. Show respect for everyone who works for a living, regardless of how trivial their job.
27. Make someone’s day by paying the toll for the person in the car behind you.
28. Become someone’s hero.
29. Count your blessings.
30. Compliment the meal when you’re a guest in someone’s home.
31. Wave at the children on a school bus.
32. Remember that 80% of the success in any job is based on your ability to deal with people.
33. Don’t expect life to be fair.
34. Being honest may not get you a lot of friends, but it will always get you the right ones.
35. Don’t worry about what others think of you. Most of them aren’t even thinking about you.
36. Comparing your life to others is an insult to yourself.
37. Never become too emotionally attached to anyone, because one day they might not be the same person.
38. The sooner you learn to be alone, the sooner you’ll be better off.
39. Don’t announce your moves before you make them. Show them the results.
40. It’s better to walk alone than with a crowd going in the wrong direction.
41. The people who ask the most from you are usually the ones who give the least.
42. Don’t take yourself too seriously, but take your responsibilities seriously.
43. Fear is not an indication that you should stop. It’s just an indication that you care.
44. Don’t make permanent decisions based on temporary emotions.
45. When you put someone on a pedestal, they’re forced to look down on you.
46. People give advice from their own perspective.
47. Not everything in your head needs to come out of your mouth.
48. Don’t do anything you’ll need to lie about later.
49. Some people only seem intelligent until they open their mouths.
50. Happiness is an inside job. Don’t assign anyone else that much power over your life.
51. You owe it to your future self, not your past self, to decide what’s next.
52. The biggest obstacle you’ll ever have to overcome is your mind.
53. You’ll realize your parents were right more times than you’d like to admit.
54. Carry yourself with the confidence of someone who doesn’t care if they’re accepted or not.
55. 99% of the things you worry about never happen.
56. If something makes you angry, ask yourself if it will matter in 10 years.
57. You only get one body. Take care of it.
58. The more someone insists that they’re telling the truth, the more likely they’re lying.
59. Your time is yours. Don’t let others dictate how you spend it.
60. You’ll never be happy if you’re constantly comparing yourself to others.
61. Don’t compare your behind-the-scenes to someone else’s highlight reel.
62. Just because you miss someone doesn’t mean you need them back in your life.
63. Looks fade, but values are what hold a relationship together.
64. Everything in life is a trade-off.
65. A true friend is someone who will speak well of you behind your back and tell you the truth to your face.
66. Sometimes the only way to move forward is to let go.
67. The more you face fear, the more fearless you become.
68. Don’t prioritize someone who treats you like an option.
69. Trying to be everyone’s friend makes you no one’s friend.
70. You have two ears and one mouth. Use them in that proportion.
71. Change is inevitable. Resistance is futile.
72. You will live many different lives within one lifetime.
73. Life gets better when you see the good in people.
74. You can cut all the flowers, but you cannot keep spring from coming.
75. People’s actions reveal their intentions more than their words do.
76. You’re not creating the future. You’re creating the present, and that creates the future.
77. Commitment will get you started, but consistency will keep you going.
78. You are allowed to fall in love again.
79. If someone is trying to bring you down, it means you’re above them.
80. Never make promises you can’t keep.
81. Going back to your ex is like putting dirty underwear back on.
82. Be open-minded, but not so open-minded that your brain falls out.
83. People will judge you no matter what you do, so you might as well do what makes you happy.
84. Just because something is difficult doesn’t mean it’s impossible.
85. Don’t listen to respond; listen to understand.
86. Every struggle you go through makes you stronger.
87. You can’t change the people around you, but you can change the people you’re around.
88. Don’t take things personally; what people say and do is a reflection of them, not you.
89. The only way to avoid criticism is to do nothing, say nothing, and be nothing.
90. Let go of the illusion of control. You can’t control everything, but you can control how you respond.
91. The most valuable things in life are free: love, friendship, and time.
92. Stop chasing people who aren’t meant to be in your life.
93. Don’t wait for things to get easier; life is always going to be hard.
94. Sometimes you just need to take a break and enjoy where you are right now.
95. The people who are hardest to love are usually the ones who need it the most.
96. Be the type of person you want to meet.
97. It’s okay to outgrow people who aren’t growing with you.
98. Don’t be afraid to start over. It’s a chance to rebuild your life the way you want it.
99. Learn how to learn from those you disagree with, or even offend you. See if you can find the truth in what they believe.
100. Being enthusiastic is worth 25 IQ points.
101. Always demand a deadline. A deadline weeds out the extraneous and the ordinary. It prevents you from trying to make it perfect, so you have to make it different. Different is better.
102. Being able to listen well is a superpower. While listening to someone you love keep asking them “Is there more?”, until there is no more.
103. A worthy goal for a year is to learn enough about a subject so that you can’t believe how ignorant you were a year earlier.
104. Gratitude will unlock all other virtues and is something you can get better at.
105. Treating a person to a meal never fails, and is so easy to do. It’s powerful with old friends and a great way to make new friends.
106. Don’t trust all-purpose glue.
107. Never use a credit card for credit. The only kind of credit, or debt, that is acceptable is debt to acquire something whose exchange value is extremely likely to increase, like in a home. The exchange value of most things diminishes or vanishes the moment you purchase them. Don’t be in debt to losers.
108. Pros are just amateurs who know how to gracefully recover from their mistakes.
109. Extraordinary claims should require extraordinary evidence to be believed.
110. Rule of 3 in conversation. To get to the real reason, ask a person to go deeper than what they just said. Then again, and once more. The third time’s answer is close to the truth.
111. Everyone is shy. Other people are waiting for you to introduce yourself to them, they are waiting for you to send them an email, they are waiting for you to ask them on a date. Go ahead.
112. Don’t take it personally when someone turns you down. Assume they are like you: busy, occupied, distracted. Try again later. It’s amazing how often a second try works.
113. The purpose of a habit is to remove that action from self-negotiation. You no longer expend energy deciding whether to do it. You just do it. Good habits can range from telling the truth, to flossing.
114. When you are young spend at least 6 months to one year living as poor as you can, owning as little as you possibly can, eating beans and rice in a tiny room or tent, to experience what your “worst” lifestyle might be. That way any time you have to risk something in the future you won’t be afraid of the worst case scenario.
115. The more you are interested in others, the more interesting they find you. To be interesting, be interested.

116. To make something good, just do it. To make something great, just re-do it, re-do it, re-do it. The secret to making fine things is in remaking them.
117. The Golden Rule will never fail you. It is the foundation of all other virtues.
118. If you are looking for something in your house, and you finally find it, when you’re done with it, don’t put it back where you found it. Put it back where you first looked for it.
119. Saving money and investing money are both good habits. Small amounts of money invested regularly for many decades without deliberation is one path to wealth.
120. To make mistakes is human. To own your mistakes is divine. Nothing elevates a person higher than quickly admitting and taking personal responsibility for the mistakes you make and then fixing them fairly. If you mess up, fess up. It’s astounding how powerful this ownership is.
121. You can obsess about serving your customers/audience/clients, or you can obsess about beating the competition. Both work, but of the two, obsessing about your customers will take you further.
122. Show up. Keep showing up. Somebody successful said: 99% of success is just showing up.
123. Separate the processes of creation from improving. You can’t write and edit, or sculpt and polish, or make and analyze at the same time. If you do, the editor stops the creator. While you invent, don’t select. While you sketch, don’t inspect. While you write the first draft, don’t reflect. At the start, the creator mind must be unleashed from judgement.
124. If you are not falling down occasionally, you are just coasting.
125. Perhaps the most counter-intuitive truth of the universe is that the more you give to others, the more you’ll get. Understanding this is the beginning of wisdom.
126. Friends are better than money. Almost anything money can do, friends can do better. In so many ways a friend with a boat is better than owning a boat.
127. This is true: It’s hard to cheat an honest man.
128. You are what you do. Not what you say, not what you believe, not how you vote, but what you spend your time on.
129. Hatred is a curse that does not affect the hated. It only poisons the hater. Release a grudge as if it was a poison.
130. There is no limit on better. Talent is distributed unfairly, but there is no limit on how much we can improve what we start with.
131. Be prepared: When you are 90% done any large project (a house, a film, an event, an app) the rest of the myriad details will take a second 90% to complete.
132. When you die you take absolutely nothing with you except your reputation.
133. Before you are old, attend as many funerals as you can bear, and listen. Nobody talks about the departed’s achievements. The only thing people will remember is what kind of person you were while you were achieving.
134. For every dollar you spend purchasing something substantial, expect to pay a dollar in repairs, maintenance, or disposal by the end of its life.
135. Anything real begins with the fiction of what could be. Imagination is therefore the most potent force in the universe, and a skill you can get better at. It’s the one skill in life that benefits from ignoring what everyone else knows.
136. When crisis and disaster strike, don’t waste them. No problems, no progress.
137. On vacation go to the most remote place on your itinerary first, bypassing the cities. You’ll maximize the shock of otherness in the remote, and then later you’ll welcome the familiar comforts of a city on the way back.
138. When you get an invitation to do something in the future, ask yourself: would you accept this if it was scheduled for tomorrow? Not too many promises will pass that immediacy filter.
139. Don’t say anything about someone in email you would not be comfortable saying to them directly, because eventually they will read it.
140. If you desperately need a job, you are just another problem for a boss; if you can solve many of the problems the boss has right now, you are hired. To be hired, think like your boss.
141. Art is in what you leave out.
142. Acquiring things will rarely bring you deep satisfaction. But acquiring experiences will.
143. Rule of 7 in research. You can find out anything if you are willing to go seven levels. If the first source you ask doesn’t know, ask them who you should ask next, and so on down the line. If you are willing to go to the 7th source, you’ll almost always get your answer.
144. Don’t ever respond to a solicitation or a proposal on the phone. The urgency is a disguise.
145. Buying tools: Start by buying the absolute cheapest tools you can find. Upgrade the ones you use a lot. If you wind up using some tool for a job, buy the very best you can afford.
146. Following your bliss is a recipe for paralysis if you don’t know what you are passionate about. A better motto for most youth is “master something, anything”. Through mastery of one thing, you can drift towards extensions of that mastery that bring you more joy, and eventually discover where your bliss is.
147. I’m positive that in 100 years much of what I take to be true today will be proved to be wrong, maybe even embarrassingly wrong, and I try really hard to identify what it is that I am wrong about today.
148. Over the long term, the future is decided by optimists. To be an optimist you don’t have to ignore all the many problems we create; you just have to imagine improving our capacity to solve problems.
149. If he doesn't do anything to try to keep you why are you trying so hard stay.
150. Ask yourself this: "Do you really want to be loved like this for the rest of your life?"
151. có 2 thứ sẽ cứu sống theo nghĩa đen: ăn uống và luyện tập
152. 2 thứ không nên giữ trong lòng, lời khen và tiếng cười
153. 2 thứ nên dùng hành động: một là họ quan trọng với bạn và những người không muốn dính dáng
154. 2 thứ không nên vội vã: đánh giá tiêu cực, hoặc khi đang làm giữa chừng một điều gì đó
155. Give love, but don't exhaust yourself Be peaceful, but don't become passive Have patience, but don't develop arrogance Be open to love, but don't force a connection
> *A collection of unsolicited advice. Some I learned the hard way. Some I found and agreed with.*

*still updating*
### on people
157. Some will expect you to be quiet to keep their peace.
158. People who obsess over you initially are in love with an idea, not you. They don't know the real you.
159. Those that want to live, are made to suffer; and those that want to die, are forced to go on living.
160. The weak fear the truth and resent those who speak it.
161. What people became isn't what they wanted but who they have to be.
162. Self-obsession is tolerable. Forcing it on others is repulsive. This applies to everything - looks, morals, relationships, choices.
163. People cannot give you what they don't have.
164. Some relish others' moral failings to entertain their own judgement, eagerly anticipating their downfall.
165. If problems only occur with certain people, it's them. Not you.
166. They despise you for what you possess and mock you for what you lack. They look down on you when you’re poor and fear you when you’re rich.
167. People who seem to be the kindest are the most dangerous.
168. People often choose popular actions not because they believe it’s the right thing to do, but because it’s the option that makes them feel secure.
169. Sincerity and pretense, nobility and meanness, hatred and love can coexist. It is no imperfection, merely a reaction in a world full of greys.
170. The quickest way to know somebody is to lend them money.
171. No friend's presence should bother you more than your solitude.
172. Disguised small talks is rarely genuine concern. They're just probing to ensure you are not outpacing them.
173. Promptness is a sign of respect.
174. Perseverance does not equal worthiness.
175. Don’t let the disrespect of those you lowered your standards for get under your skin.
176. Sometimes people need to be understood more than to be loved.
### on yourself
177. Your wounds might be the result of your kindness.
178. Self pity and excuses are lazy.
179. Your lowest points are yours alone. Others can't see them, especially if they want something from you.
180. Decisions will upset you or others. Accept it. It won't change.
181. Some paths are meant to walk alone because it's personal.
182. Solitude feels uneasy when you overvalue others' presence.
183. Self-esteem in love is only selfishness.
184. If you need peace, you need to let go.
185. Let jealousy teach you gratitude, anger for compassion, the uncontrollable for letting go, annoyance for patience.
186. No apology should be made for wrong being, such as anger or confusion.
187. Your loyalty is not to be questioned if your well being is already affected.
188. Your healing cannot depend on someone that doesn't understand their wrongdoing. If staying means undervaluing yourself, you should move on.
189. Don’t burn yourself out trying to light the way for others.
190. Opinions of others are for understanding different perspectives; they don't have to influence yours.
### on things around you
191. Life can be challenging despite our best efforts. It's not your fault for trying and sometimes falling short.
192. Sex is a physical act. Love is a collection of ideals. Marriage is a social contract.
193. It feels the most difficult only when you start.
194. If experience is overrated, you should snip your appendix on your own.
195. It's better knowing that something might not succeed tomorrow than next year.
196. Thousands to bully one is called justice.
197. All worship masks underlying desires.
198. Suspicion is often the precursor to a guilty verdict.
199. Expectation is the precursor of disappointment.
200. Most people are transient. Move on without lingering.
201. Behind obstacles and fears often lie what you need.
202. The most successful relationships are based on lies.
203. The right words are often simple.
204. There are beautiful songs but some people just don't like music.
205. All claims lacking falsifiable evidence are opinions, not facts. Normalizing opinions as facts is the fastest route to misinformation. This includes seemingly benign daily conversations.
206. May what you care about gives you more of what you need, not less.
207. Your circle should be proud of you, not jealous.
208. When someone is rude, hateful, or mean, imagine they’re suffering from an illness.
209. Find smart people who will disagree with you.
210. Anyone can be replaced. To replace a bad person, it would have already cost many good ones.
211. Fixation on vanity is unattractive.
### what you should do
212. Be good, be excellent, be bold, but don't waste your time proving it.
213. No matter how destructive your rage feels, you're just one person out of many.
214. Learn how to do nothing and be bored.
215. Avoid sarcastic remarks, not because people aren't funny enough to understand.
216. Choose your most frequent encounters wisely, such as your shoes, your bed, your best friends, and your job.
217. Emotional wounds hurt most when inflicted by those we trust. The only right course is to learn how to regain your sense of control.
218. No explanation is needed for people you don't need in your life.
219. If you need to beat yourself up, do it once and move on.
220. Only hang out with people that energize you.
221. Master fake sincerity. Everything else falls into place.
222. Apologize immediately, genuinely, explicitly.
223. Be grateful to those who helped you to be the person you are today.
224. Sometimes you need to do things you don't enjoy to get close to what you do.
225. Don't romanticize memories. Remember the disrespect that came with them.
226. Manage your energy for the worthwhile.
227. Do the most important task first.
228. Win or lose, be a good one anyway.
229. Keep your true light hidden from acquaintances, even relatives and friends.
230. In a fight, hit first and hit hard.
231. Accept an outstretched hand and turn your back on a withdrawn one.
232. Sincerity and honesty are expensive. Reserve them for those who deserve them.
233. Don't try to change people, change how you deal with them instead.
234. Learn to react less.
235. Don't promise and agree when you're having a good time.

I don't seek revenge on you but I do hope you experience yourself in another person.