# brivv

```
65. Make no mistake about it: Computers process numbers--not symbols. We
    measure out understanding (and control) by the extent to which we can
    arithmetize an activity.
85. Although the Chinese should adore APL, it's FORTRAN they put their money
    on.
100. We will never run out of things to program as long as there is a single
     program around
114. Within a computer, natural language is unnatural
119. Programming is an unnatural act
127. Epigrams scorn detail and make a point. They are superb high-level
     documentation

    -- Alan J. Perlis
```

Programmatic email.

Augmenting natural language with programming languages.

Event-sourced email threads and thread-groups associated with "smart contract"
email templates.

Clients maintain template state, equivalent to contract state on Ethereum
blockchain. Clients can variably expose template state via API similar to web3.
Niether smart contract code nor state need be revealed to users; rather, only
an ABI must be encoded in an email.

---

What profit hath a man for all his email wherein he emaileth under the sun?
We've lost the beauty of a handwritten letter in exchange for speed -- emails
are written not to endure but to be sent and sent quickly. But there is profit
to be extracted, besides speed, from the cold medium of today.

brivv is a transhuminist project that aims to transform modern languages into
a lambda calculus-influenced argot that will make language precise where
precision is needed and allow human interactions to accumulate program state,
both ephemeral and eternal.

## Phase 1

L'email est né libre et partout il est dans les fers. Email must throw off the
chains of gmail, whose web UI has wrought great sorrow, and move towards the
decentralized model of yesteryear. Everyone should be in control of their email
server and emails should be private. [Lavabit](https://lavabit.com) and
[Protonmail](https://protonmail.com) don't even come close to what we need.

Whenever a user is ready to leave my platform and host their own email server,
the process should take 10 minutes and they shouldn't lose their identity
(email address) or email history.


## Phase 2

Email thread state, email client-compiler response type-checking. Support for
simply-typed LC.

An very simple example:

You're a lawyer who creates LLCs for clients. You have a client intake form (a
template which exists at some smart contract address in your local client) that
you send out to be filled out by 100 different individuals. The individuals
respond to your smart-contract-in-email-form using their email programs. The
clients' email programs refuse to send a message if their response doesn't
match the ABI of your intake form template. Your email program would reject any
emails that do not match your template ABI too, in case the client's email
program is buggy. After you have received all the intake forms forms from
clients, you would map over the necessary data for each client, transmit it to
London's incorporation API (also a simple, private email-based smart contract),
and wait for a new tax ID. Simple people will be able to set up apis for
everything, effortlessly. We don't need centralized servers to make APIs or
store data. Spam is much less of an issue because of cryptographic signatures
and reputation systems.

Email programs can expose template state for public contracts used for
scheduling meetings, for example. A lawyer has a calendar contract that exposes
information about when he has time for a call; certain privileged clients could
book calls automatically.

---

The largest influence on my thinking is the UI of a theorem-proved like Coq
(https://en.wikipedia.org/wiki/Coq) or Agda. Mathematicians depend on these
programs to make certain mistakes impossible to make. Similarly, this email
client will make it impossible to not respond to questions posed by a user,
e.g. attach a c.v & tell me how your mother's doing & tell me how old you are.
This is all very simple stuff, but mix into this all the other apis available,
e.g. NYSE prices, weather reports, and you've got a way to automate and
disambiguate a lot of communications.

All the robo-personal assistant companies will be made irrelevant
(https://claralabs.com/). You don't need robots to schedule things for you, you
just need to augment email with bits of argot, a precise legalese.

## Phase 3

Calculus of Inductive Constructions
