hello everybody and welcome to the free
code camp blockchain and solidity
beginner to expert full course python
edition we're going to go through
everything you need to know for
developing on a blockchain using
solidity and engaging in the future of
finance we're going to cover topics that
will teach you all the skills you need
to become a smart contract expert that
you can take with you no matter which
blockchain you're developing on
blockchain engineers are in extreme
demand and they're building billion
dollar applications almost every day at
this point at the time of filming
protocols like ave yearn.finance and
synthetics have billions of dollars of
locked value in them allowing people to
engage in decentralized finance or defy
this allows people to make censorship
resistant moves and so much more some of
these protocols with billions of dollars
are even less than a year old so whether
or not you're brand new to this space or
you've been in here a while hi my name
is patrick collins and i live in the
smart contract world i'll be taking you
through your journey to becoming a
blockchain and smart contract expert a
little bit of background on myself i'm
an engineer and developer advocate on
the chain link protocol and i also have
my own blockchain infrastructure company
called alphachain where i run different
nodes and different infrastructure for
blockchains including one of the main
technologies we're going to be talking
about today which is ethereum i love
being a pioneer in the smart contract
ecosystem and i love taking new users
like yourself along to the journey with
us and we are going to teach you to
become a smart contract expert building
blockchain and solidity applications is
building a world of more trust and
accountability it means building a
financially free future and we get to be
the ones that will go down in the
history books as the pioneers of this
space additionally blockchain and smart
contract engineering skills are some of
the most sought after in the world with
an average salary of a solidity
developer being between 150 and 175 000
in this video we're going to teach you
how to become one of these developers
and go out into the world and
participate in the world of smart
contracts in the world of blockchain
this course is ideally for engineers who
know a little bit of python programming
and you can have any level of smart
contract engineering whether you're a
complete beginner to blockchains and you
don't even know what one is or you're an
advanced solidity engineer and you're
looking to learn more this is the
perfect place for you having a little
bit of experience in other
object-oriented programming language
like javascript as well will be helpful
here too and if you're brand new to
coding in general that's all right
because we're going to take you step by
step through everything if you do want a
little bit more in-depth python coding
video there is a fantastic free code
camp video in the description if you do
prefer javascript we will also be
releasing a javascript edition of this
video as well but everything that you
learn here will be applicable there and
if you watch both you'll learn even more
you can find the entire itinerary for
this entire course along with all of the
code associated with everything that we
do and additionally discussions and
support and everything else in this
smart contract kit
full blockchain solidity course pi
github repository it has a table of
contents and then the entire itinerary
of everything that we're going to go
over in this course and like i said with
helpful tips resources for getting
support and resources for getting help
now for your convenience every single
piece of code that we're going to go
over in this video has a github
repository associated with it so be sure
to grab the link in the description grab
that github repository and look through
all the different repos that we're going
to give you if you ever get lost or need
to refer to some code or want to copy
paste some code all of it will be there
for you it'll also be a great place to
reference in the future when you're
working on some project and you want to
remember how to do something so be sure
to start and refer back to it as you
watch this video so let's talk a little
bit about some best practices for
watching this video this space moves
really quickly so if we show you some
documentation it might be a good idea
for you to open that documentation up as
well read through it as we do so you can
stay up to speed now we've packed a ton
of information in this video and studies
have shown if you try to digest a
massive amount of information in a short
period of time your retention isn't as
good so it's highly recommended that
every 25 minutes to half an hour you
take a five minute break and then every
two hours maybe you take an additional
30 minute or an hour long break you can
pause bookmark areas and come back later
and learn at your own speed there are
timestamps in the description that will
help you come back to where you left off
and you don't even have to go in order
if you want to bounce around from topic
to topic you're absolutely free to do so
we're also going to get really technical
with the fundamentals of blockchain and
if you want to just jump right into
solidity you can jump down the
timestamps below and get right into it
and if you're watching this on youtube
you can adjust the speed that i talk and
then i give this presentation so if i'm
talking way too quickly for you you can
slow it down or if i'm talking too
slowly for you you can have me speed up
so be sure to set me at the pace that
you like best you are highly encouraged
to pause come back and ask questions the
blockchain in smart contract world is a
very collaborative community so if you
have questions some of the best places
that you can go going to stack overflow
and tagging your question with the
specific technologies that you're
working on make an issue on the github
repo that we're working with go to stack
exchange eth and make a question there
as well jump into the discord of the
technology that you're working with or
even on github discussions if those are
there learning to become a blockchain
and solidity engineer is actually a lot
more than just learning solidity
becoming comfortable with all the tools
in the space is going to be just as
essential as becoming familiar with
solidity itself and continuing the
conversation on maybe twitter or reddit
or any of these other channels and maybe
even showing your stuff in the next
ethereum or chainlink hackathon are
going to be majorly beneficial to
increasing your skill as an engineer
now before we get actually coding a lot
of people want to understand what is
actually happening with all this
blockchain stuff what is blockchain what
is a smart contract how did this all get
started and understanding these core
fundamentals will actually shape the way
you code and architect your smart
contract applications so learning these
is really really critical
however if you're already familiar with
blockchain and you just want to jump
into the solidity feel free to grab a
timestamp from the description and jump
to that section
now since you're here though you've
probably heard of bitcoin before bitcoin
was one of the first protocols to use
this revolutionary technology called
blockchain the bitcoin whitepaper was
released by the pseudo-anonymous satoshi
nakamoto and it outlined how bitcoin
could be used to make peer-to-peer
transactions in a decentralized network
this network is powered by cryptography
and allows people to engage in
censorship resistant finance in a
decentralized manner due to some of the
features of bitcoin a lot of people took
it to be as a superior store of value
over another asset like let's say gold
and that's why it's commonly referred to
as digital gold similar to gold there is
a scarce and set amount of it on the
planet and people use it to buy and sell
similar to other assets you can read
more about the original vision in the
white paper and there's a link to it in
the description
now this was a fantastic breakthrough
and in a little bit we're actually going
to look through how blockchains can
actually work and how all of this is
possible but some people took this and
saw this technology and thought that
they could do even more a few years
later a man named metallic buterin
released a white paper describing a new
protocol called ethereum which used this
same blockchain infrastructure but
with an additional feature and in 2015
they released this project called
ethereum him and a number of other
co-founders took this blockchain
technology and applied it in ways that
people can make entirely decentralized
applications decentralize organizations
and build smart contracts and engage in
agreements without a third-party
intermediary or centralized governing
force their idea was to take the same
pieces that made bitcoin great and add
smart contracts to it and in fact this
technically wasn't even a new idea back
in 1994 a man named nick zabo proposed a
technology called smart contracts a
smart contract is a self-executing set
of instructions that is executed without
a third party intermediary they come to
life on a blockchain and these smart
contracts are really going to be the
core thing that we're going to be
working with and we're going to be
developing smart contracts are similar
to regular traditional contracts that
people make between each other but
instead of writing these contracts down
on pen and paper or typing that on the
computer it's entirely written in code
the terms of the agreement are written
in code and automatically executed by
the decentralized blockchain network
instead of being written pen and paper
and executed by the two parties or three
parties or however many parties involved
this is one of the main differentiators
between the ethereum protocol and the
bitcoin protocol now technically bitcoin
does also have smart contracts however
they're not touring complete meaning
that they don't have the full range of
capabilities as a turing complete
application like ethereum this is
actually an intentional move by the
bitcoin developers they view the bitcoin
network as an asset whereas ethereum and
the ethereum and developers viewed that
acid as an asset and also a utility for
people to build these smart contracts
now these smart contracts are
revolutionary technologies and we're
going to talk a little bit more about
what their advantage is in a little bit
but they actually come with a fatal flaw
with what's known as the oracle problem
these blockchains are deterministic
systems and we'll learn why they're
deterministic very soon and this
determinism means that they're a walled
garden meaning that everything that
happens in these smart contracts and on
this blockchain happens in this little
box now of course if you want these
smart contracts to actually be these
digital superior agreements then they
need some way to interact with the real
world and get real data and external
outside the blockchain computation this
is where oracles come into play oracles
are devices that bring data into a
blockchain or
execute some type of external
computation so great so oracles are the
solution now blockchains can talk to the
real world right
well not quite our blockchains and smart
contracts are these decentralized
applications and in order for them to
stay decentralized that means they would
also need to get their data and external
computation from a decentralized manner
as well your on-chain logic will be
decentralized on the blockchain but
you'll also need your off-chain data and
external computation decentralized as
well combining these on-chain logic
settlement layers and these off-chain
data and external computation
builds what's called hybrid smart
contracts and a large majority of d5
applications in the largest applications
today are these hybrid smart contracts
this is where the protocol chain link
comes into play chain link is a
decentralized modular oracle network
that allows you to bring data into your
smart contracts and do external
computation and it's these hybrid smart
contracts that can have this on-chain
settlement and interact with the real
world in some meaningful way chain link
is an incredibly powerful oracle network
because it allows us to get data get
randomness do some type of upkeep or
really customize our smart contracts in
any way we want and elevate them to do
anything that we want them to do now
throughout the course when we're talking
about smart contracts oftentimes we are
also talking about hybrid smart
contracts smart contracts is used a
little bit interchangeably with hybrid
smart contracts but just know that when
we say hybrid smart contract we're
talking specifically about smart
contracts with an off chain component
now throughout this video you'll hear
people say smart contract you'll hear
people say decentralized protocol
decentralized application or dap and
they kind of all are a little bit
interchangeable a decentralized
application is usually a combination of
several smart contracts
and when we start coding some solidity
you'll see what a singular smart
contract or singular contract looks like
smart contracts are going to be what we
code write and deploy for the majority
of this video and learning some of these
fundamental concepts will allow us to be
better smart contract and better
solidity developers now since its
inception the ethereum protocol has
given rise to many new paradigms and
industries including d5 nfts
dows or decentralized autonomous
organizations
layer twos and so much more
and a couple of other protocols have
taken this ethereum vision and gone in a
different direction with it like polygon
polka dot or avalanche if we learn the
core basics of smart contract
development on the ethereum platform all
these skills translate to these other
chains as well so don't worry about
learning a specific tool or chain
because most of them work together
pretty seamlessly
now there are a few exceptions to this
rule and there are some smart contract
platforms aka blockchains that don't use
solidity however learning the
fundamental skills here will still
translate to every single other
blockchain
and ethereum is by far the most popular
and most used smart contract blockchain
or smart contract protocol you'll also
hear those words used a little
interchangeably as well sometimes i'll
say blockchain or sometimes i'll say
smart contract platform smart contract
protocol and the like similarly chain
link is the most popular and powerful
decentralized oracle network and is
going to be the one that we're going to
focus on here chain link is also
blockchain and smart contract platform
agnostic meaning it'll work on ethereum
avalanche polygon polka or really any
blockchain or smart contract platform
out there
even in this introduction we've already
learned a lot so let's do a quick
summary of what we've talked about
bitcoin was the first application to
take the blockchain technology into the
limelight and into a meaningful way
bitcoin is a sort of digital gold able
to make transactions between users as
almost a sort of currency ethereum takes
this blockchain technology one step
further but you can also build smart
contract or decentralized applications
decentralized autonomous organizations
and more because you can code with smart
contracts these smart contracts can then
access external data and external
computation outside the blockchain using
what's called oracles chain link is the
most powerful decentralized oracle
network and allows us to build these
hybrid smart contracts which is a
combination of decentralized on-chain
logic settlement layer and any
decentralized external off-chain data or
computation hybrid smart contracts and
smart contracts are often used
interchangeably now you're probably
asking yourself a lot of questions right
now like what makes bitcoin so
interesting what makes it like a digital
gold and how are these smart contracts
going to add any value to the real world
and that's what we're going to go into
now so before we get into the
nitty-gritty of how these blockchains
and how these smart contracts actually
work from a low level let's go
high level and talk about some of the
features and massive advantages that
blockchains and smart contracts have
over our traditional environments the
first feature that these have is they
are decentralized and you'll hear this
term used a lot because it has a massive
benefit blockchains are decentralized
meaning there's no centralized source
that controls the blockchain the
individuals that make up blockchain are
known as node operators and they are the
independent individuals running the
software that connects the whole
blockchain together it's all these
different independent individuals that
make the blockchain and blockchain like
networks decentralized we'll dive deeper
into that concept later great example of
why this is so fundamentally
groundbreaking is if we go back to what
happened recently even with robinhood
and gamestop gamestop shares were no
longer allowed to be bought because a
centralized entity didn't want them to
be bought anymore so they
flipped a switch and nobody could buy
that stock anymore essentially having a
single entity controlling the entire
financial market the fact that a single
entity has the power to make these
choices for us is a travesty and
blockchain is here to solve that there's
a narrative here called the bankless
narrative where users can actually live
in a world where they don't have a bank
banks while good in their own right have
a history of doing some shady things
they also have the power to potentially
freeze your funds not letting you
withdraw or move or do anything because
they are a centralized entity that again
can
flip a switch and control how you
interact with your life every day being
free of these centralized entities have
this much power and this much control
over your life has widespread positive
ramifications transparency and
flexibility
everything that's done on a blockchain
and all the rules that are made can be
seen by everyone there's no backdoor
deals there's no shady happenings
everything that happens on chain you can
see this means that there's no special
information that a few have
everyone has to play by the same rules
and everyone can see exactly what those
rules are
now additionally this doesn't mean that
everything you do is tracked the
blockchain is pseudo-anonymous so you
can create different accounts and you
can interact with it in many different
ways this leads me to my freedom point
but i'll get there in a second speed and
efficiency have you ever tried to make a
withdrawal from the bank and it took
three to five days
all the bank is doing is adding and
subtracting numbers
basic first grade math
so why does it take so long because
blockchains are verified by a
decentralized collective the settlement
or withdrawal period in this case is
substantially faster and depending on
the blockchain that you're using it can
be from
10 minutes all the way down to just a
couple of seconds in the stock trading
or hedge fund world it can actually take
up to a week for your buy or sell of a
stock to go through security and
immutability blockchains are immutable
which means they can't be changed and
because of this it means that they can't
be tampered with or corrupted in any way
shape or form this allows us to have
massive security on our data on our
transactions and anything of the like if
your computer goes down and your backup
computers go down
in the regular world your data is gone
if all your data is on those two
computers you're out of luck on a
blockchain if several nodes go down it
doesn't matter because as long as one
node and the entire system is running
the data is safe and secure there are
thousands or hundreds of thousands of
nodes running these blockchain softwares
meaning that everything that happens
happens and is immutable and won't
change
hacking the blockchain is nearly
impossible and substantially harder than
hacking a centralized entity and this is
also much more secure in the asset sense
as well instead of having gold in a
vault or contract written on a piece of
paper or on your computer you have a
asset that is
locked on the blockchain forever and all
you need to do to access it is have a
private key or mnemonic
which is essentially a password so you
don't have to lug your gold around or
lug your contracts around with you it is
always on the blockchain smart contracts
in particular remove a massive conflict
of interest in the traditional world
when we engage with users or individuals
they don't always have our best
interests at heart
a lot of them are usually self-motivated
in some sense and there's nothing wrong
with that that's how a lot of people are
however when we make an agreement with
them this agreement can have a massive
conflict of interest with the user who's
supposed to execute that agreement
let's take insurance for example if i
pay an insurance provider 100 a month
i'm paying them a hundred dollars and in
the event that i get hit by a bus we've
made an agreement or a contract that
they're going to pay my medical bills or
bail me out however they have this
massive conflict of interest insurance
companies aren't in the business of
giving out money they're in the business
of making money so even though they've
signed this agreement when this event
occurs they still don't want to pay this
money out to me and if they can find a
loophole in the contract they will
because that is what they are motivated
to do so they sign this agreement but
it's not in their best interest to do so
so they have this massive conflict of
interest and this is native in all of
the agreements that we make today they
are the ones who decides whether or not
they're going to execute their agreement
giving execution power to the party that
doesn't want to execute something has
often led to frustration now the
follow-up is you can always sue them and
go through this process but now you're
wasting all this time going through this
long process to get something that you
should have originally gotten in the
first place
this leads me to one of the biggest
value adds to smart contracts smart
contracts allow us to engage in
trustless and trust minimized agreements
we currently live in a world of
brand-based agreements
if i engage in some agreement and i
don't like the service that i'm provided
my alternative to this is to waltz down
the street to another brand to another
service who's going to make the exact
same set of promises to me and then i
have to trust them that they're going to
execute faithfully smart contracts allow
us to move from this brand based
agreements to
math-based agreements these math-based
agreements we don't even have to trust
that they're going to do the right thing
hence the name trustless one plus one is
always going to equal two in a math
world whatever the code determines is
the input output that's exactly what's
gonna happen every single time
now for me these really all add up to
two major pieces
freedom
and trustless all these pieces allow us
to live in a world that's more
accountable more trusting more friendly
and
just better it allows us to work in an
environment and a universe where things
just
work
it allows us to do the freedom to engage
with other people how we wish because
there's no centralized controlling body
influencing every action that we make
all the rules are the same and nobody's
getting special treatment
this brings out this new world of
economic opportunity as well and as our
lives become more and more digital we're
constantly being bombarded with
centralized services that want us to use
their interface so they can profit on
how we interact and force us or push us
to making the decisions that they're
motivated for us to make smart contracts
decentralized applications and
blockchain
allows us to be free of these repressors
and live in an environment that's truly
free and trustless
so with all that high level being said
let's do a quick summary of what we just
learned blockchains are decentralized
meaning that they are not controlled by
a single centralized entity it is run by
a network of independent users
transparency blockchains are transparent
everything that happens on a blockchain
everybody else can see and everybody
else can work with and see that
everyone's playing by the same rules
blockchains are quick and efficient
especially when it comes to monetary
policy settlement on blockchains are
fast and easy immutability and security
blockchains can't be changed or tampered
with or corrupted and are incredibly
incredibly secure smart contracts remove
the massive conflict of interest
traditional agreements have smart
contracts allow us to move away from
political brand-based agreements to
secure
math-based agreements smart contracts
allow us to engage in trustless and
trust minimized agreements
smart contracts are a set of
instructions which when placed on a
blockchain are self-executing pieces of
code not run by any centralized
intermediary in addition smart contracts
are typically paired with some type of
oracle to get some information about the
real world when smart contracts are
paired with an oracle they're called
hybrid smart contracts chain link is a
secure decentralized modular oracle
network used to bring data into your
smart contracts and also make some type
of external computation i also briefly
want to mention dao's or decentralized
autonomous organizations you'll hear
this referred to a lot as well
decentralized autonomous organizations
are organizations that live online and
live in these smart contracts they're
similar to a regular organization in the
traditional world however they have
people who maybe hold governance tokens
to make voting decisions or they do all
their governance on chain
on this decentralized settlement layer
giving us the freedom to engage with
each other as we please
so now that we've taken our first dive
into blockchains and smart contracts and
at least from a high level understood
why they're so advantageous let's jump
in let's get an ethereum wallet and
let's make our first transaction on a
live blockchain are you ready now let's
jump into ethereum we're going to make
our first interaction with the ethereum
blockchain and once we do this
interaction once we make this
transaction
then we're going to go back and look at
what actually happened what were the
technical implications that allowed this
transaction to go through so in order
for us to interact with the blockchain
the first thing that we're going to need
is an ethereum wallet
so i'm going to go ahead and go to
metamask because it's one of the most
popular wallets and one of the easiest
to use we're going to go ahead and
download it
i'm using the brave browser but it works
for chrome firefox or really any other
browsers
and it's just going to be a little
extension in the top right hand
of your browser
this way we can really easily see at any
time what we have in our wallet
this will store all of our ethereum
based currencies
so i'm going to go ahead and install
metamask for brave
add to brave
add extension
and now we can go ahead and get started
with working with brave this is the
first step you absolutely need to take
when starting your journey and one of
the easiest steps to take so we're going
to go ahead and get started
and we're going to create a brand new
wallet so we're going to go ahead and
hit create wallet
if you already have a wallet you can
actually import it via i have a seed
phrase and we'll talk about the seed
phrase or secret phrase in a little bit
so let's go ahead and create a new
wallet
and sure we'll agree to help out
metamask now we will create our password
make sure that this is really secure
for the purpose of this demo my
passwords are just gonna be password but
please don't have that be a password now
when i'm doing my testing when i'm doing
my coding i actually use a separate
account from the account that i actually
have real money in however if you want
to use this account and actually put
real ethereum and put real money into it
you absolutely 100
need to back this up so we're gonna go
ahead and click reveal secret words i'm
showing you guys here because
uh this is just a demo and i don't
really care however if you show this
secret phrase to anybody else they will
have access to
all funds
so everything that we're gonna do in
this tutorial we're gonna use fake money
we're gonna use not real money so it
doesn't matter however if you're going
to actually put money in here you
absolutely need to have this written
down because if you lose access to this
and or your private keys which we'll
talk about in a little bit you will lose
access to your wallet and you will lose
access to all your funds
so they give some tips like store this
phrase and a password manager like one
password write this phrase down on a
piece of paper put it in a secure
location memorize it whatever you want
to do just make sure you have this
backed up somewhere
i'm just going to go ahead and hit
download this for now and i'm going to
save it on my computer it's not best
practice to save to your computer it is
much better to use a password manager or
write it down on a piece of paper or
something
but again because we're just demoing
here
i'm going to show you it here and we're
not going to put any real funds into
this
so we're going to go ahead and hit next
and we're it's going to ask us to
make sure we and it's going to ask us to
verify that we actually have it written
down
and we're gonna go ahead and hit confirm
and great and it gives us a couple other
tips remember definitely take these tips
very seriously especially if you're
gonna use this for real money like i
said for this demo we're just gonna use
test money so it's not as big of a deal
but if you put real money in you
absolutely need to back up this seed
phrase or secret phrase or we're going
to refer to it as our mnemonic phrase
awesome now we can see the user
interface of this wallet
and depending on your browser if you
actually go ahead and look in your
extensions you can pin it to your
browser and you can even just click it
and get the same interface here let's
take some inventory of what is actually
going on in here and what we actually
have our mnemonic phrase that secret
phrase that we got
has given us access to a new account and
here's the address of our account we can
use a tool like etherscan to view
different addresses and what's been
going on with them so if we look at this
address that we just created on
etherscan we can see that no
transactions have happened it's empty it
has zero ether in it it has zero dollars
worth of value in it and this address
here
is our unique address this address
represents
exclusively this single account that we
just created we'll talk a little bit
more about etherscan in a bit as it's a
tool that we're going to use more and
more now we can even click this
circle here and we can even create more
accounts and give it a different account
name
we'll call it account 2.
this one has a different address so if
we go ahead go back to etherscan and
look this up this one has a different
address here
so we can have multiple addresses in
here and now if i click this i have two
accounts account one
and account two
the mnemonic that we've been given
gives us access to create multiple
accounts with that same mnemonic so
having that mnemonic will give us access
to every single account that's ever
created with that mnemonic this is why
securing your mnemonic is so crucial
especially if you create multiple
different accounts
now each account
has a unique identifier with them as
well so so this right here is the public
address when we copy this this is the
public address of that account
however there's also a private key to
work with this account a secret key
and we can go ahead and view it by
clicking these three dots go to account
details and export private key
put our password in and confirm
so this is going to be our private key
so this is a single
password associated with this account if
you give somebody else access to this
private key they will have access to my
account too they won't have access to my
account one because the private key of
account two is only associated with
account two the mnemonic however is
associated with all accounts and this is
why when people say store your private
keys in a safe place or store your keys
in a safe face they're usually referring
to both your mnemonic and your private
keys
if you lose your private key you lose
access to this account if you lose your
mnemonic you lose access to all your
accounts so long story short back up
your mnemonic since it has access to
everything and back up your private keys
too but just keep in mind they only have
access to the individual accounts and
great those are some of the main
security pieces here
now what else is going on in metamask is
we can see this section here that says
ethereum mainnet if we click it we
actually see a bunch of other networks
in here
so when you buy eth and when you work
with eth you're working on the ethereum
mainnet when you interact with smart
contracts or d5 or any things that we're
going to talk about later on mainnet
with real value you're going to be
working on the mainnet
however since we're engineers oftentimes
we're going to want to test our
applications or do some type of
integration tests or just make sure our
code actually works
so there's also what's called test nets
these are networks that resemble
ethereum and work exactly the same way
as ethereum does
however they're not with real money and
it's just for testing your applications
so we can even go to ether scan and look
up
brinkp ether scan
we can see the rink be test on explorer
we look up at our address and it's the
exact same
information here
nothing has gone on on rink b and this
is totally different so when we make a
transaction these are all different
networks and it says test network it's
made to be made without real money later
on we're actually going to show you how
to work with other evm compatible chains
don't worry about what evm compatible
means for now but we can work with
avalanche polygon and other applications
through this networks interface as well
so remember a testnet blockchain is a
blockchain where the currency doesn't
have any real value but it resembles and
acts exactly like the ethereum mainnet
so we can test our applications
so we can test and practice our
applications
in fact what we're going to do right now
is make our first transaction on the
rink b test net and this will simulate
exactly what it's like to make a
transaction on the ethereum mainnet so
we're going to go to this application
called the rink b faucet this is where
we're going to make our first
transaction ring b is going to be one of
two test nets that we're actually going
to work with the other test net that
we're going to work with is going to be
coven it's important to know how to
switch between test nets and evm
compatible chains which is why we're
going to be working with both for now
we're just going to be working with rink
b
a faucet is a tested application that
gives us free test ethereum hence why it
has no value because anybody can get it
for free from one of these faucets so to
get tested ethereum with this
application we actually have to post a
tweet or a facebook post
with this tweet so i'm actually going to
i'm going to sign in real quick
and now that i'm signed in i can post
this tweet requesting faucet funds into
and this is where i'm going to put my
address
on the rinkby ethereum test network i'm
going to go ahead and tweet that out
now that i have this
we're gonna copy link to tweet
and we're gonna place it in here and
we're gonna hit give me ether and we're
gonna say 18.75 ether for three days and
it said funding request accepted for
patrick alpha c
into this
and what we can do then
is if we take this address again
we go over to rink b ether scan
we now see that the balance is 18.75
and we can even see that
in our wallet on the ringbeat network we
have 18.75 eth but again if we look at
mainnet we have nothing there if we look
at robson we have nothing there if we
look at rink b we have 18.75 right so
these are very different networks and
we've just made our first transaction
we've been given
18.75 eth and if we refresh this page we
also see that this is our first
transaction that was made
some account sent us 18.75 ether
from
this account to us and we can actually
even look at the details of this
transaction
etherscan is what's known as a block
explorer block explorers are
applications that allow us to see
details of things that happen on a
blockchain easily we can see the
transaction details of this transaction
here and whenever we work with smart
contracts we will also see them in a
transaction similar to what we're seeing
right here and again we'll talk about
that soon now we can see a number of
information here we see a unique
transaction hash this hash or this
unique identifier uniquely identifies
this transaction
as the key of what this transaction is
we see that it was a successful
transaction this is the block number
which we'll talk about in a little bit
we see it was from this unique account
which looks like they did a ton of
transactions because this is the faucet
account
to our account that we created
value was 18.75 ether
and then we have these transaction fees
gas price gas limit and gas used now gas
refers to the fee paid to node operators
for successfully including a transaction
in a blockchain
now exactly how this works is actually
going to change pretty soon but the
concept is basically anytime you want to
change the state of blockchain whether
this is sending some ethereum or making
any type of transaction
you actually have to pay a little bit of
ethereum or a little bit of that native
blockchain token to actually execute
that transaction whenever we do
something on the blockchain
it costs gas and if we do something that
would take a lot of energy for the
blockchain to do it will cost more gas
so if i send a single transaction that's
going to cost 21 000 gas however if i
were to do if i were to send a
transaction that called the smart
contract function and did a whole bunch
of other stuff it would cost more gas so
we see here when we got sent
18.75 eth whoever sent us that eth also
paid the blockchain miners or the
blockchain validators a little bit of
ethereum to include our transaction now
we actually get to pick how much of a
fee we want to send with our
transactions so let's look at another
example so
in our accounts in metamask let's even
expand the view here
we have two different accounts we have
account one and account two account one
has 18.75 account two has zero
we can actually send money from account
one to account two and again remember
this is all fake money so so we're gonna
go ahead and hit transfer between my
accounts so we're gonna send money to
account two
and here's where we can see some
transaction details and we see the asset
that we're going to send which we only
have ethereum in this wallet so we're
only going to send ethereum later on
we'll learn how to get different assets
into this wallet we're going to choose
an amount i'm just going to choose to
send one and then we have these pieces
here
associated with the transaction fee so
we have a gas price in guay and a gas
limit so when we send a transaction we
can choose a gas limit we can say hey if
this transaction is going to spend more
gas than
21 000 gas we're not going to do it
we also get to set a gas price in guay
but here's the quick example of guay
versus ethereum
[Music]
one ether is
this many gray
and one gray is this much ether because
if we just said hey could you send me
.00001
that would be
kind of really obnoxious so we just just
say send me one way or send me one way
so i know we've been throwing this gas
term around for a little bit but here is
it basically simplified gas is going to
be the measurement of how much
computation something uses the gas price
is going to be how much it costs per
unit of gas a gas limit is going to be
the maximum amount of gas that can be
used in transaction so for example if we
make a transaction that uses 21 000 gas
and each one gas is one way
in price that means we're going to pay
21 000 way
in transaction fee
so back in our transaction we have we're
saying the gas price
is going to be one way so the
transaction fee is going to be the gas
that we use which will be up to this gas
amount
times the gas price so it'll be 21 000
way will be the transaction fee so then
the question is well why would we ever
bump it up why would we want to pay more
gas price why do i even have the option
to pay more well and this comes down to
block space we'll talk about this a
little bit more when we get into how the
blockchain actually works but the
blockchain can only
process so many transactions at a time
and nodes and blockchain nodes can only
process so many at a time so when i make
a transaction a node has to decide why
they want to include my transaction into
the block and if there are a ton of
people
looking to make these transactions then
the nodes are going to be highly
incentivized to pick the transactions
that are going to give them a high price
that are going to give them a lot of
money for including that transaction
so this is what's called eath gas
station and it is a a gas estimator of
the blockchain it currently says that if
you want to get your
transaction in right away it's going to
cost you 31 way to do so if you want to
get it in less than five minutes it's
going to take you maybe about 21 gway
so the gas prices of ethereum fluctuate
with how much people use it and the gas
prices of all these blockchains
fluctuate with how much people use it
so this is an important concept so
typically when you're setting your gas
price in a transaction you can take a
look-see at you know gas station and say
okay if i want mine to go in right away
i'm going to do asap if i want to go in
fast maybe i'll do you know this fast
amount standard i'll do this standard
amount but it all depends on how many
people are looking to work with this
blockchain at the same time and and as
you can see it fluctuates pretty quickly
right it just went all the way up to 46
so maybe more people are using the
blockchain now this is obviously for the
eth main net and on the test net there's
not going to be that same competition
but we can still change it anyway so if
i go ahead and do 100 for the gas price
and i hit next and i hit confirm if i go
to activity
i now have
this transaction
in my
metamask but i can go ahead and view
this on etherscan as well
and we can see this is what it looks
like when it's still processing this
transaction and now we can see that it's
passed and now if we look at the gas
price we see it's a hundred gray and
this is what we set it as when we were
working with it before so gas prices 100
way here versus our first original
transaction was just one way
now if we look at our metamask we can
see that
the funds have indeed been
subtracted from this account and they
have been added to this account now
there's one eighth in this account
awesome and you can see the activity
there's one ethan here so again the
reason that these gas prices exist is
because nodes can only put so many
transactions into a block so they're
highly incentivized to input the
transactions that are going to give them
a higher fee so in times when a lot of
people are looking to use a blockchain
prices will get very high and when very
few people are using a blockchain prices
will be very low this ether scan tool is
incredibly incredibly powerful and we'll
be using it more and more as time goes
on now here's something that's
incredibly exciting with just this
little bit of information you now know
how to interact with blockchains and
interact with the ethereum protocol so
if you don't want to learn how to code
anything you can go and you can start
interacting with ethereum and interact
with protocols with just this much
information however i know most of you
guys are here to learn how to code so
let's look under the hood of ethereum
and what is actually going on with these
transactions
and with these gas and with these
blockchains and what's really going on
let's learn all the fundamentals of a
blockchain now if you want to just go
ahead and jump into the coding go ahead
and grab a timestamp from the
description however learning exactly how
the blockchain works is going to make
you an incredibly powerful developer so
let's take a look at that first so we're
going to be going through this
blockchain demo on this site right here
now the creator of the site has a
fantastic video and a fantastic
walkthrough blockchain 101 it is right
on their site so if you're looking for
another explanation definitely check out
his video it is absolutely fantastic but
the first thing that we really need to
do in order to understand blockchain in
order to find really anything and
everything that's going on here we first
really need to understand this shot 256
hash or hashing just kind of in general
let's first understand what a hash is a
hash is a unique fixed length string
meant to identify any piece of data they
are created by putting some piece of
data into a hash function
in this example
the hashing algorithm used is sha256 now
ethereum actually uses this this right
here for its hashing algorithm which
isn't quite um sha256 but is in kind of
this shaw family but it's it's really
just another way to hash things and uh
the specific hash algorithm doesn't
matter uh so much so uh this example
uses sha-256 but you can imagine it's
the same as the ethereum hash they're
just gonna you know result in a
different hash
so what's going to happen in this
application here is whatever
data or whatever information we put into
this data section here as you can see
below this hash
changes
so what's happening is this data is
running through the sha 256 hash
algorithm and it's outputting this
unique hash so this
hash is a unique fixed length string
that's going to identify like a blank
data piece here right so if i put in you
know my name like you know patrick
collins
this is the hash that's going to
represent patrick collins right and you
can see
even when i put you know tons and tons
of data in here the length of the string
doesn't change
right
so it's always going to be the same
amount we can put
almost any amount of data in here there
is an upper limit on the max size of the
data but for all intents and purposes we
can pretty much put any length in here
and you'll see too that you know every
time i type in patrick collins
this hash is always going to be this
7e5b right i'm going to delete i'm going
to do
patrick collins again
you know seven e5b it's always this this
unique hash is always going to be
unique right it's always gonna be this
fixed length string here so now we can
take this idea right of putting this
data in here and we can move on to
uh this concept of a block so with this
block concept we're going to take the
exact same thing with this hash this
this data section right but instead of
having everything just being this this
singular data area right here we're
going to split this data up into block
nuns and data so all so what we're going
to do is we're actually going to hash
all three of these to get to get this
hash right we're going to put all three
of these we're going to say all three of
these are combined uh together we're
going to put every all three of them
into this hashing algorithm uh to figure
it out so if i type a bunch of stuff
here
we can see that block one
with nuns you know this nonce and this
data we're gonna get this hash and as
you can see actually
the screen turns red this block turned
red now
what happens when i hit this mine button
when i hit this mine button it's
actually going to take some time it's
going to think for a little bit and we
can see that the nuns here actually
changed right the nuns is different from
what it was before and
this hash now starts with four zeros
okay and then it the the back turned
green when we're talking about mining
we're talking about miners solving some
type of very difficult problem that
takes a lot of time to do now in this
example here the problem that the miners
had to solve was they had to find a nuns
or or a value in this nun section that
when hashed with at block number one
with this data
it would start with four zeros
so the problem here the miners had to
solve was to start with four zeros and
the only way for them to really do that
is kind of this brute force you know
trying stuff so they tried one okay one
didn't work okay two nope two didn't
work three no four or five six okay five
well that started with one zero but it's
not four and they have to keep trying
all these numbers until they uh get to
this one where you know let's hit mine
again
where it has four zeros at the top at
the start
now
this specific problem changes blockchain
to blockchain right ethereum has a
different problem for miners to solve um
bitcoin has different problems for minor
itself but this concept is going to be
the same
so they have to take
one block is going to be this
uh this concept is going to be all this
data it's going to be the block number
and it's going to be this nunce right
and so this nunce is the solution um is
is going to be the the number that they
use to get like the solution to the
problem right so if i go to one
here you know when i do this again
i'm gonna hit mine
and the nuns has changed right it went
from one to
thirty three thousand one hundred and
twenty eight because this is the nuns
that allowed this hash to start with
four zeros and so that's what's
happening
when uh blockchain miners are mining
they're going through this process this
very computationally intensive process
of trying to find a nuns that fulfills
whatever the problem is so that's really
it actually so that's a block and that's
really what's happening when miners are
mining they're just looking there's
trial and error brute force trying to
find this nut so so now that we know
what a block is let's go to the next
step and figure out okay well what's a
block chain so here we have an example
of what a block chain is going to look
like right we have a combination you
know we have back here in the block
section we have one what one block looks
like now here we have multiple different
blocks right each one of these
represents a different block but we have
an additional column here or we have
additional uh variable here so like
before you know we have block nuns and
data
right we have block nun's data but we
also have this thing called previous
right and so this is actually pointing
to the previous hash of the last block
so for example if we go to the the last
block in this blockchain it says
previous is 008 and if we look at the
hash of block number four it's zero zero
zero zero eight e eight and then we look
at its previous it's uh four zeros b9 we
have four zeros b9 and so on all the way
back to our first block which has
previous of just all zeros right and so
the block with the previous of all zeros
is going to be known as the genesis
block so you've probably heard that
before the genesis block it's the first
block in the blockchain where the
previous hash points to a hash that
doesn't actually exist now as you can
imagine kind of the same as how this
block worked how the block nuns and data
all go through the hashing algorithm in
the blockchain the block nuns data and
previous hash all go through this
hashing algorithm to figure out you know
what the hash is okay so if we go to
over here you know for example if i type
in you know patrick
obviously this is now no longer valid
right because this nuns uh combined with
the block the data and the previous hash
aren't gonna solve you know our problem
of having four zeros at the start right
so i'm going to go and fix that and and
that's that's kind of an easy way to see
it being broken but
but let's take a look if i break
this block right here what happens if i
if i break the data in here if i do like
trick in here you can see that both of
these
are now red both of these are now
invalid right because the block hashed
with the nuns hash with the new data
which is my name patrick has worked
hashed with the previous block
is now a brand new hash right and this
block
is still pointing to this previous hash
right here right it's pointing to this
previous block and now it is wrong and
it is messed up and now um and now it's
nuns with this previous hash is also
wrong
right and this is where when we talk
about uh blockchains being immutable
this is exactly how it's immutable right
because if i go back and i change
anything you know if i've just
typed a right here the entire blockchain
is now invalidated because none of these
are going to have
nunses that solve this equation anymore
so this is why blockchains are immutable
is because anytime you change one thing
you ruin the rest of the blockchain okay
so however though you know if if an a
was here originally we can go ahead and
mine these
we can mine all these but as you can see
you know this is going to start getting
very
computationally expensive
because i have to go redo basically the
entire blockchain
and the farther and farther down the
line you get the harder and harder it
becomes to you know rehash and redo all
these different blockchains here now
this makes a lot of sense right so we
have this blockchain it's really hard to
change something in the past but if we
do we can just go ahead and remind it
now if i'm the one who controls the
blockchain right if i'm the one who
controls this you know and i want to
change something in the past well okay
great all i got to do is change this
data here and then you know mine each
one of these and you know obviously it's
going to be very computationally
expensive but it's something that i can
do right if i'm the one who owns the
blockchain
now here's where the decentralized
nature or the distributed nature really
uh makes it incredibly powerful so we're
gonna go to the distributed tab here
which i also refer to as the
decentralized tab here
it's going to show us what a blockchain
looks like
in a decentralized manner so we have
this exact same initial setup here we
have distributed blockchain we have you
know our first block chain which is kind
of exactly as the one from here but we
also have
more than one so we have peer a peer b
and peer c and when people are talking
about peer to peer appear to be your
transactions they're really talking uh
this is kind of that concept that
they're talking about right so we have a
number of different peers who are
running this blockchain technology
they're all weighted equally right each
one of these peers or each one of these
nodes each one of these entities running
a blockchain
has the exact same power as anybody else
right so the way that we can tell very
easily which blockchain is correct or
which ones are correct are by looking at
this end
hash here right or by looking at where
we are
in the blockchain because again remember
because again remember this this hash
that this this in this last block here
is going to encompass
all of the blocks from before right
because this last hash is going to have
the previous hash here which includes
the previous hash here which this hash
includes the previous hash here in which
so this last hash is encompasses
everything in here right and we can look
we can look at the hash of pure c which
is four zeros and then e4b we can look
at the latest hash of peer b which is
four zeros e4b
and then pure a which is for zeros e4b
so all of these peers all of these nodes
all of these decentralized you know
these independent
all these independent users running this
blockchain software they're all matched
up it's very easy for their nodes to
look at each other and say hey great we
are all matched up
now
what let's say that a decides that you
know something happened on the
blockchain that they didn't like and
they wanted to go back and change
something right so let's say they change
here you know obviously
the rest of their blockchain is
invalidated and they have to spend a lot
of computational power to catch up to
speed so let's go ahead and humor it
let's say that they they did they ended
up catching up
uh they ended up catching up you know
they ended up mining everything
and now they have a valid blockchain
right it solves the equation awesome
however
in block number three
there's something new
right this is here and it shouldn't have
been here this is something that pier a
put in by themselves
all that happens now
is we look at all the blockchains that
are running the software and we're
looking at all the hashes at hash at
block number five so pier a has this new
hash now 009 bc
but peer b has a different hash 0 e4b
right so who's right is it is it pier a
with their new stuff or is it peer b
well that's where the decentralizator
comes in because then we can look at
pier c and pierce c
also has e4b so
pure b and pure c both say hey pure a
you're wrong
get out right and peer a will stop being
able to participate in the mining
rewards because they have essentially
forked uh the blockchain and started
their own little blockchain right with
their own history because they're the
only ones with this this piece of data
in block three whereas peer b
and peer c have nothing in there so that
really shows why uh in these blockchain
worlds in this decentralized world there
really is no central identity you know
pier a you know might have been
maliciously motivated to change you know
this block number three however
democracy rules right the majority rules
in the blockchain peer b and pc both say
hey you know that's cute and all pure a
but
you're wrong right that that's not right
now it might be a little abstract that
you just look at data and you know us
typing kind of random stuff in here and
think okay yeah that's that's data right
that makes sense you know just kind of
random strings in here doesn't really do
anything for us so if we actually go
over to the token section here this is
where everything really starts to make a
lot of sense so we have the exact same
setup here with peer a peer b peer c
except the difference is instead of
having kind of this this data section we
have this
tx this transaction section right and
this represents all the transactions
that are happening in this block right
so we're we're sending 25 dollars from
darcy to bingle or to bingley uh force
uh four dollars and 27 cents here uh
1922 right and it's the exact same thing
so this all these transactions are going
to get hashed in the exact same way uh
that the data is going to get hashed and
and this is why it's so powerful because
again you know if i want to be malicious
right if uh if i want to say hey i
really wanted to give jane
a lot more money from elizabeth so i'm
pure a and i go back and i change it to
100 well now
you know not only do i does my whole
blockchain
get invalidated because that was so far
so long ago but i'm not going to match
any of these other chains right and so
my blockchain is going to be excluded
from the overall blockchain so and let's
let's go ahead and fix this and it's the
same thing if down here if i become
malicious and i want to send you know i
want
uh miss audrey to have less money maybe
i want to send a dollar and i go ahead
and mind it the same thing here
this hash now this 2a1 is not going to
match
peer b's
pre-b's hash of bba and it's not going
to match pc's hash of bba as well so the
two of them are going to say hey this
your blockchain isn't valid it's not
matching the majority you know you're
out right
so that's really how these blockchains
work at a low level and it all goes back
to this this understanding this hash
idea and using it in this very
sophisticated manner uh to kind of
cryptographically prove
um you know where where stuff lies now
the way the blockchain works is that
instead of random stuff put in this data
section it's actually going to be
solidity code in here to finding ways to
interact with different blocks and
different protocols that are on chain or
as we've said before different smart
contracts
now the next question that you might be
asking is okay well
how do i know how can i be sure that i'm
the one
uh you know let's say this is let's say
i'm darcy right how can i be sure that i
was that darcy was the one to actually
send this money here how do we know that
darcy sent 25
to
bingley well this is where we get into
uh private keys and public keys and
that's what we're going to go into now
let's just do a quick recap of what
we've learned in this section so far
right we've learned that
ethereum actually runs on this ketchup
256 but you know we used shot to v6 for
this demo it doesn't really matter we're
just talking about hashing algorithms so
again a hash is a unique fixed length
string meant to identify any piece of
datum a hash algorithm or a hash
function is a function or algorithm that
computes any type of data into a unique
hash
mining is the process of finding the
solution to the blockchain problem in
our example the problem was to find a
hash that starts with four zeros
whenever a node mines a block they get
paid a little bit of that gas we were
talking about earlier for doing
something a block in a blockchain is
basically a combination of a block nonce
transaction and previous hash to create
this unique hash for this block and
again depending on the blockchain
implementation this might have a couple
other fields or might have different
fields but this is essentially what's
going on blockchains are decentralized
and distributed because
many independent users are going to run
this blockchain software and they will
check and they will compare against each
other to see which blockchains are
acting honestly and which ones are
acting maliciously in the blockchain
world majority rules the nuns here is
the answer used or the number used to
get this hash now nuns is kind of an
overloaded term it's actually used for a
number of different reasons in this case
we're using it to solve this problem of
getting you know four or five zeroes at
the stop of the hash however in ethereum
it'll also be often used as the number
of transactions from a given address so
now we're going to talk a little bit
about signing these transactions and
private keys and some other cryptography
pieces right because in this blockchain
demo here we can see we hover these
these fantastic transactions right all
these things went through but how do we
know that it was darcy who was the one
to send 25
to bingley right how do we know that
actually happened and this is where
all those pieces that we just learned
about uh in our our test net in our
metamask account are really going to
start to to come to life here a little
bit here so here we have an example of
public and private keys okay at the top
we have this private key right that was
that was randomly generated a private
key is is you know as it kind of states
is a key that you really want to keep
secret because you're going to be using
this
as kind of your secret password for all
your transactions right i can really
pick you know any
any any private key anything that i want
and with it uh
this algorithm they're going to use an
algorithm you know for ethereum in
bitcoin they both use this elliptic
curve digital signature algorithm it's a
variant of just a digital signature
algorithm and it's going to create this
this public key right i'm really not
going to go at all into kind of this
digital signature algorithm but just
know it does use some of these some of
the hash
knowledge that we just learned combined
with some other pieces
to kind of get this this public here so
i'm not going to go too deep into it but
we have this private key that we create
and we get this public key now this
public key we want everybody to have
access to right this is yeah whole world
can see this this private key we really
want it to be uh private we don't want
people to see this we're going to use
this private key as like a password to
quote unquote digitally signed
transactions and then people can verify
them with this public key so let's let's
see what this actually looks like let's
pick a random key a more secure key
right because the longer it is the more
secure it's going to be
and if we go to signatures now
right
let's say we have this
this message that we want right we'll
say hi world right we want this to be
the message what's going to happen
is this private key that we've created
we can use to sign this data right
remember how in the blockchain demo you
know we were kind of we were hashing
stuff right we were we're using this uh
shay256 hash to to get this hash well
we're doing something similar but
instead of hashing we're we're using
this digital signature algorithm to
create this message signature
now what's really powerful about how
this uh this algorithm works is that you
can create this message signature with
your private key but somebody else can't
derive your private key from the message
signature and that's what makes this
really really powerful however if we go
to verify using this public key right
and so this is the
this is that o four zero three this is
that same public key using this using
this public key
anybody can verify let's go ahead and
sign again anybody can verify
that the signature
is yours right so you have a public a
private key
just for you so you can sign things and
a public key that anybody can verify
something right so anybody can verify
this and let's say somebody tries to
fake a transaction from you they say hey
you know this is this is this is their
transaction
all they have to do is verify
that this
signature against your public key and
very easily this whole thing turns red
because
it isn't verified right the the
algorithm says hey
that's wrong so we can go ahead and take
that into transactions in this exact
same way so if i want to send money
you know if i want to send
400
from you know my address to another
address using my private key i can sign
that transaction
and anybody else in the world can then
verify this transaction right and this
is why when people say
hide your keys you know protect your
keys this is what we're talking about
in our accounts here
right if we go to
uh settings and again the only reason
that i'm showing you guys
my mnemonic in my private key is because
this is a
uh this is a dumpster account i'm gonna
throw this away at the end of this video
or i'm just not gonna put any real money
in it
um
but
when we look at our our metamask here we
have this mnemonic phrase which allows
us to
easily get these different private keys
right so
demonic phrase combined uh with you know
whatever account number will get us a
private key so demonic phrase combined
with one we're going to get this private
key and this is when we look at account
details export private key
password confirm this is going to be the
private key that we're going to use to
sign our transactions right this if
anybody else gets access to this private
key they then can sign transactions for
us and they can send transactions for us
and that's why we want to keep these
private
so it works the exact same way right so
this is why it's so important to hide
your private keys and hide your
mnemonics now
your ethereum address is actually
a piece
is actually a piece of your public key
now to get our address in ethereum all
we have to do is take this public key
that we've created with our private key
hash it using that same ethereum hashing
algorithm and then take the last 20
bytes and that's how we'll actually
derive to our um to our address here now
knowing the exact methodology of how to
get the address doesn't really matter
because it could change blockchain to
blockchain and could even change an too
but just know that that is essentially
how kind of these addresses are derived
right there's some derivative of the
public key right because the public key
is public and you know using the public
key in kind of any public way is is
totally fine
but not the private key so that is how
we sign our transactions note though
this isn't how we send the transaction
so so this is just going to sign it
create a transaction for us to send
we'll learn later on how to send these
transactions
so that was a lot of information there
too let's do a quick recap your public
key is derived by using a digital
signature algorithm on your private key
right and you want to keep your private
key private at all times because you're
going to use your private key to sign
transactions
signing transactions with your private
key you are the only one who can
actually do this because you can't get
the private key from a message signature
however using your public key you can
anybody can very easily verify that a
signature that's signed by you is in
fact signed by you in our metamask our
private keys are located in this account
details section you just hit
show private keys and type in your
password and you'll get your private key
here
a quick note here is often times when
using your private key somewhere they
want it in hexadecimal form so if we're
going to use our private key
for something like brownie which we'll
go into later we need to actually append
in a 0x to the front but we'll get into
that later
and the address
of your account is derived from this so
if you think about it your private key
creates your public key which then can
create your address and there's a little
barrier
or a big barrier here
because your private key you want to
keep private and your public key and
your address can all be public
information awesome so now that we know
all the cryptography pieces and all the
little nitty gritties of how the
blockchain actually works and how our
signatures work and how everything
sticks together let's talk a little bit
about how this works in actuality and
what's really going on now for a lot of
this each different blockchain has
slightly different algorithms and
slightly different metrics and criteria
for doing a lot of the stuff so when
we're talking about these specific
implementations keep in mind the exact
algorithm might be a little bit
different but the concepts are all still
going to be exactly the same hashing and
hash function is going to be the same no
matter where you look a decentralized
blockchain is going to be the same no
matter where you look how it's actually
implemented is going to be a little bit
different now traditionally when you run
an application you know be it a website
or something that connects to some
server you are interacting with a
centralized entity and unlike how we saw
with the blockchain with multiple
different peers it's going to be run by
a single centralized group now it still
could be run on many different servers
but all those servers are still going to
be controlled by the same centralized
group blockchains as we saw run on a
network of different independent nodes
when we saw peer a peer b peer c those
were different examples of different
independent users running the blockchain
technology on their own node now when i
use the term node i'm usually referring
to a single instance of a decentralized
system so when i say a single node when
i'm talking about a blockchain i'm
talking about one of those peer a's peer
b's pcs running that blockchain software
i'm talking about one server running
this technology and again it's this
network it's this combination of these
nodes interacting with each other that
creates this entire blockchain what
makes this so potent too is that anybody
can join the network and that's why
there's decentralized the barrier to
entry is a little bit of hardware
requirements you're getting the correct
materials to run the software and then
you running the software anybody can
join these networks and participate and
that's what makes it truly decentralized
in fact you can go to github right now
and run your own ethereum node in a few
seconds now in the traditional world
applications are run by centralized
entities and if that entity goes down or
is maliciously bribed or decides that
they want to shut off they just can't
because they're the ones that control
everything blockchains by contrast don't
have this problem if one node or one
entity that runs several nodes goes down
since there are so many other
independent nodes running that it
doesn't matter the blockchain and the
system will persist so long as there is
at least one node always running and
luckily for us most of the most popular
chains like bitcoin and ethereum have
thousands and thousands of nodes and as
we showed in our demo if one node acts
maliciously all the other nodes will
ignore that node and kick that out or
even punish it in some systems because
they can easily check everybody else's
node and see okay this one is out of
sync with the majority and yes majority
rules when it comes to the blockchain
each blockchain keeps a full list of
every transaction and interaction that's
happened on that blockchain and we saw
if a node tries to act maliciously
then all their hashes are going to be
way out of whack and they're not going
to match everybody else this gives
blockchains this incredibly potent
immutability trait where nothing can be
changed or corrupted so in essence we
can think of a blockchain as a
decentralized database and with ethereum
it has an extra additional feature where
it also can do computation in a
decentralized manner now let's talk
consensus proof of work and proof of
stake because you've probably heard
these before and they're really
important to how these blockchains
actually work we went through that
blockchain example and we did that
mining feature this is what's known as
proof of work proof of work and proof of
stake fall under this umbrella of
consensus and consensus is a really
important topic when it comes to
blockchains consensus is defined as the
mechanism used to reach an agreement on
the state or a single value on the
blockchain especially in a decentralized
system i briefly alluded to this
consensus mechanism in our blockchain
example when i said if one changes
something and the other two
don't then majority will rule and kick
that one out this is part of that
consensus mechanism now very roughly a
consensus protocol in a blockchain or
decentralized system can be broken down
into two pieces a chain selection
algorithm and a civil resistance
mechanism that mining piece that we were
doing or or the proof of work algorithm
is what's known as a civil resistance
mechanism and this is what ethereum and
bitcoin currently use please note that
depending on when you're watching this
if eth2 is out then it's no longer proof
of work now proof of work is known as a
civil resistance mechanism because it
defines a way to figure out who is the
block author which node is going to be
the node who did the work to find that
mine and be the author of that block so
all the other nodes can verify that it's
accurate civil resistance is a
blockchain's ability to defend against
users creating a large number of
pseudo-anonymous identities to gain a
disproportionately advantageous
influence over said system
and in layman's terms it's basically a
way for a blockchain to defend against
somebody making a bunch of fake
blockchains so that they can get more
and more rewards now there are two types
of the civil resistance mechanisms that
we're going to talk about here namely
proof of work and proof of stake let's
talk about proof of work a little bit
more in depth first in proof of work
this is silver resistant because a
single node has to go through a very
computationally expensive
process called mining which we
demonstrated earlier to figure out the
answer to the blockchain's riddle of
finding that correct nonsore or whatever
the blockchain system has in place in
proof of work this works because
no matter how many pseudo-anonymous
accounts you make each one still has to
undergo this very computationally
expensive activity of finding the answer
to the proof-of-work problem or the
proof-of-work riddle which again in our
demonstration it was finding a nunce
with that first four zeros but again
each blockchain might change the riddle
work or change the problem to be a
little bit different in fact some of
these blockchains make this riddle
intentionally hard or intentionally easy
to change what's called the block time
the block time is how long it takes
between blocks being published and it's
proportional to how hard these
algorithms are so these problems
actually can change depending on how
long they want the block tone to be if
the system wants the block time to be
very very long they just make the
problem very very hard if they want to
be very short to make the problem a lot
easier we'll talk about civil attacks in
a little bit and how they can affect the
system but with proof of work it's a
verifiable way to figure out who the
block author is and be civil resistant
now you need to combine this with a
chain selection rule create this
consensus now there are some consensus
protocols that have more features but
very very roughly these are the two
pieces that we're going to look at the
second piece is going to be a chain
selection rule
how do we know which blockchain is
actually the real blockchain and the
true blockchain now on bitcoin and
ethereum they both use a form of
consensus called nakamoto consensus and
this is a combination of proof of work
and longest chain rule the decentralized
network decides that whichever
blockchain has the longest chain or the
most number of blocks on it is going to
be the chain that they use this makes a
lot of sense because every additional
block that a chain is behind it's going
to take more and more computation for it
to come up
that's why when we saw in our
transaction we actually saw
confirmations the number of
confirmations is the number of
additional blocks added on after our
transaction went through in a block so
if we see confirmations is two it means
that the block that our transaction was
in has two blocks ahead of it in the
longest chain now i do want to point out
that a lot of people use proof of work
as a consensus protocol and i do want to
say that this is a little bit inaccurate
but sometimes people use it
interchangeably proof of work is a piece
of the overall consensus protocol which
in bitcoin and ethereum one's current
case is nakamoto consensus nakamoto
consensus is a combination of proof of
work and its longest chain rule both
equally and very very important now
proof of work also tells us where these
transaction fees and these block rewards
go to remember how when we made this
transaction we had to talk about gas and
a transaction fee so who's getting paid
who is getting this transaction and this
transaction fee is going to the miners
or the validators in a proof of work
network they're called miners and in the
proof of stake network they're called
validators there are a little bit
different and we'll get into that when
we talk about proof of stake in this
proof of work system all these nodes are
competing against each other to find the
answer to the blockchain riddle remember
in our example it was to find a hash
that has four zeros at the start and
again depending on the blockchain
implementation that riddle is going to
be a little bit different but all the
nodes are trying as many as possible to
try to get this answer first why because
the first node to figure out the answer
to the blockchain rule is going to get
that transaction fee they're going to
get paid from that now when a node gets
paid they actually get paid in two
different ways one is going to be with a
transaction fee and another piece is
going to be the block reward remember
how we talked about alternating the gas
price or the way on our transaction well
that's the transaction fee that we're
going to pay to these blockchain nodes
for including our transaction the block
reward is given to these nodes from the
protocol from the blockchain itself
you've probably heard of the bitcoin
having before the having is referring to
this block reward getting cut in half
and it's supposed to be cut in half
roughly every four years this block
reward increases the circulating amount
of whatever cryptocurrency that is being
rewarded for example on ethereum the
block reward is giving out ethereum and
on bitcoin the block reward is giving
out bitcoin so these nodes are competing
against each other to be the first one
to find this transaction to be the first
one to find the answer to this problem
so that they can be the ones to win both
this block reward and your transaction
fee some blockchains like bitcoin for
example have a set time when they are no
longer going to give out block rewards
and the miners or the nodes are only
going to get paid from transaction fees
now this gas fee again is paid by
whoever initialized the transaction when
we got our funds from the faucet there
was some server and somebody else was
paying the transaction fee for us
however when we sent ether from one
account to another our first account
actually paid some transaction fee to
send that ether in proof of stake
there's also a gas fee but it's paid out
to validators instead of miners and
we'll talk about that in a little bit
now let's talk about two types of
attacks that can happen in these
blockchain worlds let's talk about the
first one being the sybil attack the
simple attack is when a user creates a
whole bunch of pseudo-anonymous accounts
to try to influence a network now
obviously on bitcoin and ethereum this
is really really difficult because the
user needs to do all this work in proof
of work or have a ton of collateral in
proof of stake which again we'll talk
about in a bit the other more prevalent
attack is what's known as a 51 percent
attack now as we saw as part of our
consensus protocol these blockchains are
going to agree that the longest chain is
the one that they're going to go with so
long as it matches up with 51 percent of
the rest of the network
this means that if you have the longest
chain and you have more than 51 percent
of the rest of the network you can do
what's called a fork in the network and
bring the network onto your now longest
chain now sybil attacks obviously are
when a single node or a single entity
tries to affect the decentrality of the
network by pretending to be multiple
different people although they're just
the same person or entity and like i
said it's really difficult to do in
proof of work and proof of stake so you
can see now that blockchains are very
democratic whichever blockchain has the
most buy-in and is the longest is the
blockchain that the whole system is
going to corroborate when nodes produce
a new block and add to the longest chain
the other nodes will follow this longest
chain that the rest of the network is
agreeing with add those blocks to their
chain and follow up so very small
reorganizations are actually pretty
common when a blockchain picks a block
from a different longest chain puts it
on and then has to
swap it out for another block and
continue with a different blockchain
however if a group of nodes had enough
nodes or enough power they could
essentially be 51 of the network and
influence the network in whatever
direction that they wanted this is
what's known as a 51 attack and it's
happened on blockchains like ethereum
classic which is not ethereum this is
why the bigger a blockchain is the more
decentralized and the more secure it
becomes so after you watch this video
and you become a blockchain engineering
expert i definitely recommend you run a
note as well because you are going to
increase the security of the network as
a whole by running a node so proof of
work is fantastic because it allows us
to very easily protect against these
civil attacks and keep our blockchains
decentralized and secure
however it has some drawbacks as well
proof of work costs a lot of electricity
because every single node is running as
fast as they can to win this race to get
the rewards this leads to obviously an
environmental impact now since proof of
work and nakamoto consensus a lot of
other protocols have taken this idea and
gone in a different direction with a
different civil resistance protocol a
lot of them with the intention to be a
lot more environmentally friendly and
the most popular one right now is proof
of stake there are some chains that are
already using this proof-of-stake
protocol and that are live and thriving
some of them are like avalanche solana
polygon polkadot and terra and
additionally ethereum has decided to
upgrade to eth2 which will have this of
stake algorithm as well it'll also have
some other features which we'll talk
about in a bit now as a quick aside all
the tools that we're going to learn here
are still going to work in eth2 so
depending on when you watch this
everything here is still valid so let's
talk about proof of stake now again this
is a different civil resistance
mechanism instead of solving this
difficult problem proof of stake nodes
put up some collateral that they're
going to behave honestly aka they stake
in the example of ethereum 2 nodes put
up some ethereum as a stake that they're
going to behave honestly in the network
if they misbehave to the network they
are going to be slashed or removed some
of their stake
obviously this is a very good civil
resistance mechanism because if you try
to create a whole bunch of anonymous
accounts
then each one of those accounts you have
to put up some stake and if you
misbehave you're going to run the risk
of losing all the money that you put up
as collateral in this system miners are
actually called validators because
they're no longer binding anything
they're actually just validating other
nodes now unlike proof of work which
every node is racing to be the first one
to find the block in proof of stake
nodes are actually randomly chosen to
propose the new block and then the rest
of the validators will validate if that
node has proposed the block honestly as
we saw with our cryptography lesson it's
usually very easy for other nodes to
verify if a proposal or a transaction is
honest now randomness is a really
important topic when we're talking about
blockchains because keep in mind these
blockchains are deterministic systems
they're walled gardens from the rest of
the world and as you know a determinic
system by definition can't have random
numbers so how do we choose the random
validators in the system well it changes
from blockchain to blockchain and
actually choosing the node will change
blocks you to blockchain but in eth2
they're using what's called randow at
least for the original implementation
this is a decentralized autonomous
organization that collectively chooses
the random number and collectively
chooses which node is going to run next
we aren't going to dive too deep into
this because there's a good chance that
this might change in the future but we
will go into randomness solutions in
blockchain later on in this course now
proof of stake obviously has some pros
and cons as well pros are that again it
is a great civil resistance mechanism
and a great way to figure out who the
author of a block should be the other
pros are that it's way less
computationally expensive to figure out
the new block because instead of every
single node on the network trying to do
this only one node needs to do this and
then the rest of the nodes just need to
validate it the cons are that it's
usually considered a slightly less
decentralized network due to the upfront
staking costs it costs to participate
now this gets into a little bit of a
philosophical battle on how
decentralized is decentralized enough
and i think that's up to the community
to decide and as we progress i think
we'll learn more and more about how
decentralized is decentralized enough
the general consensus amongst blockchain
engineers though is that proof of stake
is very very decentralized and very
secure this massive environmental impact
improvement is one of the two main
reasons why eath is shifting to eth2 it
reduces the environmental impact by up
to 99 percent now these are the main
pieces of proof of work and proof of
stake but i did want to talk about
another concept that's really important
in these ecosystems and that is
scalability when we were talking about
gas prices we were saying that the gas
prices can get really high if a lot of
people want to send a transaction
because a block only has so much block
space and the nodes can only add so many
nodes so when a lot of people want to
use a blockchain the gas price
skyrockets
this is not very scalable because if we
want to add more and more people to
these blockchains it's going to cost
more and more to use the blockchains
because more people are going to want to
get into these blocks this means that
there's kind of a ceiling to how many
people can use the system because of the
financial constraints that will get
imposed as gas prices keep rising
ethereum 2 is not only attacking the
environmental impact of proof of work by
switching to proof of stake but they are
also implementing this new methodology
called sharding and sharding is a
solution to this scalability problem a
sharded blockchain really just means
that it's going to be a blockchain of
blockchains there is a main chain that's
going to coordinate everything amongst
several chains that hook into this main
chain this means that there's more
chains for people to make transactions
on effectively increasing the amount of
block space that there is sharding can
greatly increase the number of
transactions on a blockchain layer 1.
now there's another term that might be
the first time you heard it a layer 1.
we're going to talk about layer ones and
layer twos in terms of scalability
really quickly as well a layer one
refers to any base layer blockchain
implementation bitcoin's a layer one
ethereum's a layer one avalanche is a
layer one these are the base layer block
chain solutions a layer two is any
application that is added on top of a
layer one added on top of a block chain
some examples of layer twos are going to
be chain link arbitrarily or optimism
arbitrary and optimism are very
interesting because they are layer twos
that also look to solve this scalability
issue arbitrary and optimism are what's
known as roll-ups and they
roll up their transactions into a layer
one like ethereum we're not going to go
too deep into rollups and how they
actually work but all you really need to
know is that a rollup is kind of like a
sharded chain they derive their security
from the base layer from the layer one
like ethereum and they bulk send their
transactions onto the layer one they
solve some of the scalability issues by
being another blockchain that people can
make transactions on still on kind of
this base ethereum layer
now they're different from side chains
because side chains derive their
security from their own protocols roll
ups derive their security from the base
layers so arbitrary optimism for example
is going to be just about as secure as
ethereum there's some fantastic guys in
there that go a little bit deeper into
rollups and i've left a link in the
description for you all right so we just
talked about a lot of stuff so let's do
a quick recap before moving on ethereum
and bitcoin are currently both
proof-of-work blockchains that follow
nakamoto consensus however ethereum is
moving to ethereum two which will be a
proof-of-stake sharded blockchain civil
attacks are prevented due to protocols
like proof of work and proof of stake 51
attacks grow increasingly harder with
the size of blockchain so you should run
a node consensus is the mechanism that
allows a blockchain to agree upon what
the state of the blockchain is sharding
and rollups are solutions to scalability
issues on layer ones
a layer one is any base blockchain
implementation like bitcoin or ethereum
a blockchain scalability problem is that
there's not always enough block space
for the amount of transactions that want
to get in them this leads to very high
gas prices and again gas prices are how
much it costs to interact with a
blockchain
so we've learned a ton in this video so
far
everything that you went over is going
to make you 10 times better as a
developer because yes being a good
developer means you understand the code
at a very technical level
but if you can understand the overall
architecture as well you can make the
informed decisions about how to
architect your design or how to build
your software in however you want to do
so so with all that being said it's
finally time to jump into some solidity
and jump into some code so let's do this
now again
in the description of this video there
is a link to this github repository
that's going to be the home base for all
the code that we work with in this
tutorial we scroll down to this main
section this readme there's a table of
contents in here
we can go to lesson one simple storage
and we'll have links helpful tips the
itinerary of what we're going to learn
and everything else that you need to
work with here all the code that we're
going to be working with is located in
this simple storage link that we can go
ahead and click it's in its own
different repository we can go ahead and
click the file to see all the code that
we're going to be working with so let's
jump into it additionally back in our
full blockchain solidity course right at
the top
there's this resources for this course
section if you have questions engaging
in github discussions stack exchange
ethereum and stack overflow are going to
be great places to get help and get
support i highly recommend making a
stack overflow
stack exchange ethereum
and a github account so you can
participate and engage with the
community
welcome to the remix ide or the remix
integrated development environment this
is going to be where we're starting to
teach you how to work with solidity and
work with smart contracts and deploy to
blockchains we're going to use remix to
get us up to speed as it has a lot of
nice features that allow us to really
see and interact with blockchains and
really see what's going on but
eventually we're actually going to move
off of remix to another platform
but all the solidity that we're going to
learn here obviously is going to apply
everywhere as well when you come to
remix there's a whole lot of different
plugins like solidity learn eth soul
hint linter and a whole bunch of other
plugins as well i'm going to go ahead
and start by clicking the solidity
plugin but we're not going to use any of
these plugins for now but later on you
can kind of go back and learn a little
bit more about what these plugins do so
let's start perusing let's start coding
some things on the left hand side over
here is where we're going to interact
with everything so let's go ahead and
click the files up here now you can
always go back and peruse this a little
bit more and in fact i highly encourage
you to because that's how you're going
to learn the most the quickest but for
us we're actually just going to go ahead
and start with our own brand new file
we're going to create a little
application that can store information
on the blockchain for us and this is our
first project that we're going to do in
solidity so we're actually going to
create a new file
and we're going to call it
simple
storage dot soul all solidity has an
extension of dot soul at the end stands
for solidity now let's take inventory of
what we're going to be working with here
this is the solidity compiler tab
it compiles all the solidity code down
to machine understandable code or
machine language here there's a whole
bunch of different parameters we can
choose when working with sliding we
choose the compiler version we can
choose the language which we're only
going to be working with solidity the
evm version don't worry about this for
now so let's code our first solidity
contract here
now we are going to use something a
little bit special here when we actually
deploy these we're going to use a
javascript virtual machine
so we're going to use a virtual machine
that's going to simulate actually
deploying to a test net or a real
network we're not actually going to
deploy on a real network we will
in a little bit but just to get started
we're going to work with a javascript vm
which is kind of a fake environment for
now okay
testing locally and understanding how to
test locally will make your
coding experience a lot faster as you
saw when we sent some transactions some
of them actually took some a lot of time
to actually deploy we don't want to have
to spend that much time waiting around
for our tests to actually finish so
we're going to use a javascript vm to
kind of dummy it for now but let's just
start coding and go from there
so the first thing that you're going to
need in any solidity program is the
solidity version so that's always going
to be at the top of your solidity code
it's defined by doing pragma solidity
and the version
we're going to be using some version
between
0.6.0
and 0.9.0
so we're saying we want to use anything
between 0.6
and 0.9 and and as a force of habit i
just automatically hit command s
whenever i write anything so that's why
you saw some of this pop up here we can
hitting command s or control s depending
on if your windows or not we'll hit this
compile button and we'll compile
everything for us
now if we want a specific version of
solidity we can also do 0.6.0
and if i go ahead and hit command s or
compile
our compiler will automatically convert
to 0.6.0
however if i try to do 0.8.0 with my
solidity at 0.6.0 it's going to give us
an error it's going to say the source
file requires a different compiler
version
we're using 0.8.0 and this is 0.6.0 so
we're going to go ahead and hit compile
and it's going to automatically move
down to 0.6.0
we can also
do carrot 0.6.0
and this will allow us to work with
really any version of 0.6
it'll work all the way up to 0.7 where
if we hit command s or control s there
it'll give us an error so this only
works with any version below 0.7 and
above 0.6 we're going to be using
version
0.6.6 however in future contracts that
we work with we're actually going to
work with different versions of solidity
the reason we're going to be changing
versions throughout this course is that
solidity is a constantly updating
language being good at switching between
versions is going to make you an
incredibly powerful smart contract
engineer the next thing that we're going
to do is we're going to define our
contract
so contract is a keyword in solidity
which stands for our smart contract that
we're going to create you can think of a
contract similar to a class in java or
any other object-oriented programming
language so we're going to give our
contract a name here we're going to call
it simple storage
and we're going to add this little curly
bracket to say this
is the contents of our contract simple
storage
and i went ahead and hit command s and
we can see it is compiling successfully
you could hypothetically deploy this
right now and this would be a valid
contract so great job for making it this
far now in solidity there are many
different types that we can work with
let's go into some of the types of
solidity we can have integers aka whole
numbers they can be uint as in an
unsigned integer meaning they're not
positive or negative we can also have an
int
and we would define a variable by doing
you in 256 favorite number
equals 5.
so we have
an unsigned integer you went 256 means
this is an integer of size 256 bits
so we can have this be upped this number
be up to 256. you can also do uint
favorite number equals 5 but if you want
to be a little bit more precise a lot of
protocols and a lot of smart contracts
will do the whole name like you and 256.
we can also have
booleans booleans are true false so we
can have boolean
favorite bool
equals
true so this favorite bool would be true
it could also be
false
we can have strings
string
favorite
string
equals
string
a string is a string of text here right
it's going to be some word or phrase or
really any of these keystrokes here
similar to the unsigned integer we can
have an int
256
favorite
int
equals negative 5
so it could be positive or negative we
can have an address
which is going to be some type of
ethereum address
so we could do address
favorite address
equals
and then we can even copy right from our
metamask
and just paste it right in here
this is going to be a valid address here
you'll also notice that we end all of
our statements with a semicolon
we can have a bytes object
size 32 bits
favorite bytes
for our example
we're just going to use the word cat
because cat is a string which can be
converted down into a bytes object by 32
means that there's 32 bytes in this
variable favored bytes we can also do
bytes 2 bytes 3 bytes 5 etc with the
maximum size of bytes 32
for example we can't do bytes 64. we're
going to be talking about some other
variables as well like arrays and
mappings but let's just stick here for
now if you want to learn more about the
different types and the different
variables that you can use head over to
the solidity documentation and there's a
link in the github and the description
to show you this section for now for our
simple storage let's say we only want to
store numbers we don't want to store
anything else
so we're just going to go ahead and
delete everything and just have uint256
favorite number
at the top now in solidity if i do this
favorite number actually does get
initialized even though i didn't have it
initialized to 5. if i leave it blank it
gets initialized to the null value in
this case it would be initialized to 0.
so for now let's just not initialize it
to anything that way it'll get
automatically initialized to zero this
means that when we deploy this contract
as of right now favorite number will
start off as zero if you get confused
you can also make a comment on this you
could say
this will get initialized to zero
this double slash here is the way to
make comments in solidity and it won't
get executed as code so we can write
whatever we want as long as it's
preceded by two backslashes
now let's go ahead and create our first
function
functions or methods are self-contained
modules that will execute some task for
us and in solidity it's the exact same
thing they're defined
by the keyword function
let's make a function called store
that will change the value of this
favorite number here
so we're going to call store and we're
going to allow it to be past a variable
so we're going to allow it to be passed
a variable of type unsigned integer 256
and we're going to call it underscore
fave
or it
number we're going to make this a public
function which we'll get to in a minute
and all we're going to do
is we're going to set
favorite number
equals to whatever variable we passed in
favorite number so this in its simplest
form is how you can define a function
now just to visualize what we're working
on so far let's go ahead and deploy this
contract so we can actually start to
interact with it so if we hit this
button this will bring us to the deploy
tab and will allow us to deploy our
smart contract here
using our javascript vm it's given us a
fake account with some ethereum in it it
has 100 ethereum in it to start and same
as before anytime we want to interact
with the blockchain we have to pay a
little bit of gas even in our fake
virtual machine here and we want to
simulate that so you'll see it has some
of the same parameters here as making a
transaction like gas limit for example
when we deploy a contract it's going to
cost a little bit of ethereum or a
little bit of gas to do so
so let's go ahead and hit this deploy
button and see what happens so once we
deployed with this virtual machine a few
things happened
we have
remix kicking out this section down here
saying great job you've deployed
something and if we scroll down it says
transactionsrecorded1 we can look at all
the transactions we've recorded
and we can see it says deployed
contracts and we have a contract here
that we've deployed now let's zoom out
just a hair here so we can see
everything a little bit better in this
simple storage contract we see this big
store button because there's one public
function that we can actually interact
with so we can add
this number here and we'll hit store and
you'll see again we have a completed
transaction
and if we look at our contract
we'll have paid a little bit more gas
right we'll have paid a little bit more
to interact with this function because
again anytime we want to make a state
change in the blockchain we have to pay
a little bit of gas the reason metamask
isn't popping up is because we're kind
of doing it in this simulated
environment so this is great however it
looks like we can't actually see
what our favorite number is we can't
actually look at it so how do we
actually make sure that we can view this
favorite number well let's add another
parameter to this as well
if we add public
to our favorite
number we recompile by hitting command s
or hit the compile button
we delete this contract and we redeploy
and scroll down
now we'll see two buttons pop up
this blue button to show us favorite
number which again is initialized to
zero
and we have the store function
so let's talk a little bit about why
this public variable allowed us to see
this new button this new favorite number
button this public keyword defines the
visibility of the variable or the
function there are currently four
different types of what's called
visibility in solidity there's external
public
internal and private we're mostly going
to be working with public for now but
it's important to know how the rest of
these work public functions can be
called by anybody including variables
so oddly enough variables are a function
call to just look at them and return
whatever that variable is an external
function means it can't be called
by the same contract it has to be called
by an external contract so if in this
contract
i had this be external
i couldn't call
the store function
i couldn't call the store function
inside this function
because the function is external it
means somebody outside of the contract
has to call this function internal
functions however can only be called by
other functions inside of this contract
or in its derived contract
and then private is the most restrictive
as private functions and state variables
are only visible for the contract they
are defined in and not derived contracts
now the reason that we didn't see
favorite numbers show up in our original
contract deployment is that if we don't
give a state variable a visibility it
will automatically get set to internal
so if we want other people to be able to
read it we have to change it to public
now let's see how this interaction
actually works
if we hit the favorite number button
right now we'll get this call thing that
shows up and it'll show us right here
that
the value of
favorite number is zero
now this function however is set so that
whatever value we pass it is going to
change the favorite number to whatever
we pass it as so if we pass one two
three hit store
that transaction goes through
and then hit favorite number we can see
the value is now one two three
now i will also be using transactions
and smart contract interactions and
function calls a little bit
interchangeably that's because on a
blockchain whenever you call a function
or whenever you make some state change
to the blockchain you're actually also
making a transaction that's what makes
this whole thing so powerful and again
that's why making a function call or
deploying a contract costs a little bit
of gas now the reason we can access this
favorite number variable inside this
function
is because favorite number has this
global or contract scope so even if we
made union 256 tests equals 4 or
equals equals 4 we wouldn't be able to
use this variable outside of this
function
right because it's self-contained it's
self-contained inside this bracket
and
if i were to make another function
store two perhaps
public
2 doesn't know that this test variable
exists
functions only know about the variables
that are in the same scope as them so
favorite number is in this global scope
because the only bracket that's above
them is simple storage and test is in
this store scope because it has two
brackets above it it has it's inside of
the store function and inside of this
contract simple storage
store two isn't inside of this store
function or this store scope so it can't
access this test variable
so let's go ahead and make this back to
public
and we'll compile again i'm hitting
command s to compile but you can go
ahead and click the button if you like
and let's get rid of this now as you saw
when we deploy this
there's this button here that we can
click called favorite number we can also
make a function called
retrieve and make it a public function
that is of type view
and returns
uint256
and all this is going to do
is return
favorite number so we're going to talk
about views and returns here
so i'm going to go ahead and compile
i'm going to go ahead and delete delete
this contract i'm gonna go ahead and
deploy it now
and we can see
now we have
two functions or two blue buttons here
we have retrieve and we have favorite
number
if i change favorite number by calling
the store function favorite number and
retrieve will both now say it's one two
three
so then the question might be well why
is this one orange and these two are
blue
and the key relies in this view function
or this view keyword there's two special
keywords that define functions that you
actually don't have to make a
transaction on
and those keywords are view
and pure
a view function
means that we want to read some state
off the blockchain so we're just reading
off the blockchain if we're reading off
the blockchain and we're not actually
making a state change then we don't need
to make a transaction
these blue buttons are blue because they
are view functions public variables also
have view functions that's why both of
these are blue
this technically is a view function and
when i click it i get to view and i get
to read the state off the blockchain
retrieve is the same way we could have
this without a return but it wouldn't do
anything pure functions are functions
that purely do some type of math we'd
have you in 256 favorite number public
pure and just have favorite number plus
favorite number
so we're doing some type of math here
but we're not actually saving state
anywhere
we're going to do this math but we're
not going to save this favorite number
anywhere we're not going to save
anything deploy this now this pure
function
we would have this retrieve function one
two three it's blue as well because it's
again not going to change the state of
the blockchain so view functions and
pure functions are both can have this
blue color
now the reason that nothing shows up at
the bottom is because we didn't return
anything
all we're doing is we're saying add
these two numbers together and that's it
in order for this function to give us
something back we need to have it return
something so if we go back
to this retrieve
to this retrieve function we have to
define what we're going to return when
we're defining this function so we're
going to say this is a public function
it's a view function because we're going
to read some state and it's going to
return a unit 256.
so favorite number is of u 256 so that's
what we're going to return
our public variable favorite name is
also a view function that returns a
un256
for now let's just remove that so we can
work with this retrieve function
so let's go ahead and deploy
so now we see we don't have this
favorite number button anymore because
it is no longer a public function
because again it gets initialized to
internal so we can't actually view it
now keep in mind later on we're going to
talk about how everything on chain you
actually can see
and we'll talk about that a little bit
later though so retrieve is going to do
0
we can call store
and now retrieve is going to be 1 2 3.
now this application is great so far it
allows a single person to store a
favorite number and then go ahead and
retrieve it
later which is fantastic but what if we
want a list of people or a group of
people
and store their favorite numbers or what
if we want to associate a favorite
number with a single person well what
can we actually do now we have a whole
number of different choices but the one
that we're going to talk about is using
a struct structs are ways to define new
types and solidity they're almost like
creating new objects as well
so we can create a struct
called type people
and allow it to start storing a favorite
number associated with a certain people
so inside of our struct we can have
different types as well
so we have a uin256
favorite number
and we could also have a string
name
now we have a new type of type people
that has a favorite number and a name
inside of it now what we could do
with destruct is we could say
people
public
person
equals
equals people
and then inside we add the variables so
we could say
favorite number
favorite number is
2
and name
is
patrick
and of course the semicolon at the end
and again i'm hitting command s to save
but you can also go ahead and compile
in the compile tab
so let's go ahead and delete this
contract and see what this looks like
now
so now we've deployed this new contract
and we have this person struct which at
the zero index
is the favorite number and the variable
stored in the first index is going to be
the name storing variables and solidity
always works in this numeric index
fashion in fact in contract simple
storage uint 256 favorite number is at
index 0. if we were to add another
object here like
boolean favorite bool
this would be at index one
if we were to add bool
favorite
bool2 this would be at index
two zero
one
two
and it works the same in structs this is
at index zero inside the struct this is
at index one inside the struct
so we can see the variables associated
with this person we're gonna go ahead
and delete this for now because
instead of just creating one person we
actually want to create a whole list of
people so how do we create a list of
people let's delete that contract
and what we can do is we can make what's
called an array an array is a way of
storing a list or a group of some object
so as you're starting to see the way the
syntax works for defining any type of
variable is going to be the type of the
variable
the visibility of the variable like
public or if you don't declare it it
gets initialized to internal
and then the name of the variable
it works the same with arrays so we'll
make a people array the people array
is the type
we'll make it public
and we'll call it people
now if we deploy this contract
we go and see we now have a people array
but if we click this button
you'll see that
nothing shows up
the reason is because it's an empty
array to start with right we don't have
anything inside of it
now this type of array that we've
created is what's known as a dynamic
array it's a dynamic array because it
can change its size right now it's a
size 0 and if we added something to it
it's of size one you can also create
arrays of a fixed size so if i were to
do people one public people this array
could only have a maximum of one person
inside of it
so we're going to work with a dynamic
array though because we want to add an
arbitrary number of people into here so
let's go ahead and create a new function
called add person where we can add a
person to this array
so we'll do function
add person
string
memory name i'll talk about this memory
keyword in a minute
uin256
favorite
number
and then we'll make this a
public function
and inside we'll do we'll add this
person to our array the way to add a
person to your arrays is using the push
method
so we're going to push
a new people or a new person
and we're going to give it
those variables again
so we're going to give it so we're going
to give it favorite number
is this variable that we passed in here
oops this needs a bracket
and then we're going to give
the name
going to be this underscore name
and then end bracket
oops
zoom out again here just so i can see
stuff
this needs a semicolon
and perfect
now in that last clip we saw this little
red box pop up whenever a little red box
like this pops up after you compile it
means you have a compile error this
means that there's something wrong with
your solidity code or your salinity
syntax and it won't compile and deploy
properly red is going to be this compile
error now we're going to see a bunch of
yellow warnings in the future if you get
a little yellow pop-up these are okay to
ignore but they usually have some
helpful tips about something that might
be going wrong in your code so to
summarize if it's red if it's red it's
broken if it's yellow you might want to
check it out but it could be okay so we
can see we have our new function add
person
where we pass a string memory name and a
unit 256 favorite number and then we
create
this people person
this people object here and then we push
it
onto our people array
and i'm going to show you another way we
can actually create a people person
is just by passing
favorite number and name
and getting rid of this other bracket by
passing favorite number and name
because we know
that
the zeroth index of people is favorite
number and the first index of people is
name so we can also create a new person
by adding it like this now let's talk
about this memory keyword here now in
solidity there's more or less two ways
to store information you can store it in
memory
or in storage
when you store an object in memory it
actually means that it'll only be stored
during execution of the function or of
the contract call
if we hold it in storage
that means that that data will persist
even after the function executes a
string in solidity is actually
technically not a value type a string is
actually an array of bytes a variable of
type string is actually a special type
of array that we can append text to so
because it's technically an object we
have to decide where we want to store in
memory or in storage and since we only
need this name during the execution we
can have it be string memory name and
then when we create this new people
object we will create a new copy of this
name variable into storage memory means
that after execution delete this
variable and storage means keep it
forever if this is a little bit
confusing for you just know that for now
when you use a parameter that's going to
be a string for one of your functions
you need to call it string memory so
let's go ahead and deploy this contract
and see what happens now
now we have this new function add person
and since we are making a state change
here we can see that this indeed
is a orange button instead of being a
blue button so we can add in here a
string name we'll add
patrick and we'll say his favorite
number is 2.
again right now if we look at people
we see people 0 there's nothing in here
if we retrieve there's nothing in here
so we're going to add person patrick and
now if we hit people of 0 we can see
that the person at the zerowith index in
this people array
is going to be
string patrick
if we try at one there's nothing in here
let's add another person
we'll add
becca and her favorite number will be
24.
let's add her now if we hit one we see
favorite number 24 string name is becca
and retrieve is so showing up blank
because we haven't touched favorite
number awesome this is great we can just
keep adding people
however there is kind of an issue here
what if i'm looking for a person what if
i'm looking to find
becca and find her favorite number in
this array
what if i know her name but i don't know
her favorite number is there an easy way
for me to find that favorite number
without having to triage the entire
array there's another data structure
called a mapping so let's create this
new data structure
so this data structure is going to be of
type
mapping a mapping takes some type of key
and spits out whatever variable it's
mapped to so in this case if we're
saying we want to use the name becca to
find her favorite number we would say
the string becca
is going to be mapped
to the uint 256 favorite number and
similar to
all the other variable declarations the
first part is going to be the typing so
this is going to be a type mapping of
string
mapped to un256
we're going to give this public
visibility and we'll call it
name
to favorite number and without adding
any other functions that work with it if
we deploy this we can see we have this
blue button because we're not making a
state change name to favorite number and
if we type in becca in here
obviously nothing's going to happen
because we haven't added this
mapping in yet
so in our ad person down here let's even
have this ad person also add to the
mapping so we can do name
to favorite number
and then the key is going to be this
name so of becca we're going to say
we're going to map the name becca
to
the favorite number
now we're going to go ahead and compile
again i'm hitting command s
deploy
we can scroll down here
if we look up backhand here
we're going to get nothing
however
if we add
becca
and her favorite number being 24
this add person is going to add it both
to the array
and to this mapping now if we look up
name to favorite number we see that
becca returns 24. now one other thing i
want to show you guys just because
compilers are going to yell you if you
don't have them is typically at the top
of these contracts you want to add an
spx license identifier basically
solidity and the ethereum community
found out that
trust in a smart contract can be better
established if source code is available
and
in terms of legality and copyright it
just makes life a lot easier if you add
that license identifier right at the top
of your solidity we're going to use the
mit license identifier because it's the
most open license out there it means hey
anybody can use this code and we don't
care so you'll see a majority of
salinity contracts have this spx license
identifier mit at the top and compilers
will yell you a lot less awesome we now
have a contract that we've decided that
we liked it's got mappings it enables us
to actually store people and their
favorite numbers this is fantastic we've
done all of our testing in this
javascript vm and we've decided you know
what we want to deploy this to an actual
test net or an actual mainnet how do we
actually deploy this so that other
people can interact with this contract
we are again going to use rink b because
that's what we use to make our first
transaction
now again you will need some type of
test ethereum in your test and wallet so
again if you get lost
you can always just google rink b
faucet
or ring b test net faucet
and find a faucet or a better
alternative would be to come to the link
token contracts in the chain link
documentation at
docs.chain.link and
scroll down or just look up rink b this
linked token contracts page has the most
up-to-date faucets for any test net that
it supports so for example we get a test
and eth faucet right here which also
just happens to be that exact faucet
that we used earlier the only thing you
need to change
in remix is we need to change from
javascript vm to injected web3
and metamask will actually pop up and
say hey would you like to connect to
this application
anytime you're working with a web3
application or a web application that
wants to access your funds or work with
your metamask metamask will pop up and
ask for authorization first this is
really good so that we know which
applications we're actually connected to
so we're going to go ahead and say next
connect and we can see here
that we've even connected here and that
our account on the main network
has zero eth
and remix even tells us hey you're on
the main network so let's go ahead and
switch
to the rink b network
and we can now see
we're on the rink b network and we have
17.74 eth on this ring b test network
injected web 3 means we're taking our
meta mask and injecting it into the
source code of the browser here and
that's the difference between injected
web 3 and javascript vm web web3
provider is if we want to use our own
blockchain node or our own web3 provider
when we do injected web3 we're saying
our web3 provider is our metamask which
will work perfectly for what we're
trying to do so since we already have
some tests on ethereum let's go ahead
and deploy this and see what this would
actually look like if we deployed to a
mainnet the process is going to be
exactly the same right the only
difference was we would be on the main
net instead of rank b so let's go ahead
hit deploy we'll uncheck publish
published ipfs
hit deploy metamask will pop up asking
if we want to do this transaction
because remember
we are deploying a contract we are
changing the state of the blockchain so
we have to pay a little bit of gas fee
for it so we're going to go ahead and
hit confirm
and we get
a link to ring the ether scan similar
exactly as we saw before when we made a
transaction the difference here
is that instead of sending ethereum to
somebody we're actually making a
transaction on the blockchain to create
a contract after a short while it will
show up here on etherscan with a success
the number of block confirmations which
again is the number of blocks appended
to the block that included our
transaction
we see from which is our account here
and we see two is this new contract that
we just created and we can even click it
and we see
that
there's this unique transaction hash
that created a new smart contract and
same as working with the vm we have all
the exact same functions in here and you
can see if i hit retrieve
these three functions since they're not
making a state change you can just click
them and no transactions will be made
however what do you think is going to
happen if i hit store
if you guessed metamask will pop up you
guess correctly
again we see the familiar pieces here we
have a gas price gas limit
go ahead and hit confirm
we get another transaction here and once
this transaction goes through
we should be able to call our retrieve
function and see a new number
if we call it now
nothing shows up because our original
transaction hasn't succeeded but i bet
if we look at it now
okay it's still indexing but it looks
like it's been included if we hit it now
we do indeed see this value here
and we can do the same thing with adding
a person we'll add becca we'll say her
favorite number is 24.
metamask will pop up we'll go ahead and
confirm the transaction and if i look up
becca and the name to favorite string
right now it's going to show nothing
because our transaction hasn't gone
through yet
but if we wait a little bit i should
probably spell her name right we do see
24.
and if we look at the zeroth index we
also see becca's been added here as well
now all the solidity code that we wrote
and when we interacted with this
blockchain here
all this solidity was compiled down to
the evm also known as the ethereum
virtual machine
a lot of the blockchains out there today
are what's called evm compatible
and that means that all this solidity
and all these functions that we're
creating
can still compile down to evm and
deployed on their blockchain you'll find
out a little later when we look to work
on a non-ethereum based chain that we
can still deploy our solidity smart
contracts to these other chains as well
but that's a term you'll hear more and
more the ethereum virtual machine or ebm
now take a break give yourself a high
five because you just deployed your
first smart contract and you learned the
basics the fundamentals of solidity so
huge congratulations on how far you've
gotten now in our second projects we're
going to take the fundamentals a step
further and start going into the more of
the intricacies of solidity but just as
a quick recap the first thing you always
got to do in your smart contracts is
name the solidity version
then you'll have to name your contract a
contract in solidity is like a class and
defines all the functions and parameters
of your contract
there's many different types in solidity
like unsigned integer 256 boolean and
bytes
we can create structs in solidity we can
create arrays in solidity we can create
mappings in solidity we can create
functions in solidity
view functions don't make a state change
memory and storage are two different
ways to initialize where a variable is
going to be saved
all the solidity code that we're working
with gets compiled down to the ethereum
virtual machine and last but not least
congratulations on taking your first
step in learning solidity let's move on
to the next project
all the code tips and links that we're
going to be working with can be found in
our course repository
we can scroll down to lesson two
storage factory
click it here and we can see all the
code we're going to be working with good
luck all right so we've done it we've
got our first contract out of the way
we're understanding some of the basics
of solidity now let's move onward let's
get a little bit more advanced with what
we're going to do
with our smart contracts and let's build
what's called the factory pattern of
smart contracts so we have our simple
storage contract here which is great it
allows us to store
numbers and store favorite numbers
associated with different people and
this is great what if though i want to
have a lot of these simple storage
contracts deployed i want to give people
the ability to generate and deploy their
own lists based off of this contract
this is where the factory pattern comes
into play so let's go ahead and create a
new contract so in this contracts folder
i'm going to do new file
we're going to call this
storage
factory
dot sol
and now we'll have a storage factory.sol
now the way that we're going to do this
is that you need simple storage and
storage factory in the same folder
i have both of them in this contracts
folder but if you have them outside or
in a different folder that's okay just
make sure wherever they are they're in
the exact same folder so let's figure
out how to get a contract to actually
deploy another contract we're going to
add those basic pieces that we added in
that simple storage.sol we'll add the
spdx
license
identifier
which will be mit
we'll choose our solidity version which
will be pragma
solidity
and we'll say anything in the six range
and then we'll create our contract we'll
say contract
storage
factory
and we'll create our brackets here and
i'm going to do command s or compile
whatever you want to do things are
looking good here great so how can this
contract
deploy a simple storage contract well
the first thing that we're going to need
to do is actually import this simple
storage into our storage factory
contract
we need to import it so that
our storage factory contract knows
what a simple storage contract even
looks like
the way that we can import it is by
doing the command import and then the
file path that the simple storage is
located so the file path for this is
going to be at dot slash
simple
storage dot soul
this means that simple storage is in the
exact same directory as storage factory
doing this line is equivalent to copying
everything in this contract bit
coming over to storage factory and
pasting it above
you can even save and compile and have
two contracts in the same file now
what's interesting about having two
contracts in the same file is that when
you go to deploy
you'll actually have a choice of which
one you want to deploy and it's the same
thing if i do that import statement so
if i delete all this
and i go back to import dot slash
simple storage dot sol in our deploy tab
still
you'll see that we still have our choice
of which contract we actually want to
deploy
so this is how we actually import a
contract or import any type of file that
we want so that our contract knows what
that contract looks like and can do so
if we want this contract to then be able
to deploy a simple storage contract
we're of course going to have to create
a function that can do that
so we'll do function
we'll call it create
simple
storage contract
we'll make this a public function
we'll do our little open and close
bracket in here the way we can generate
a contract of simple storage type is by
using a new keyword so let's create a
simple storage variable
we'll say a variable of type
simple storage contract we'll name this
variable
simple storage
with a lowercase s
equals
new
simple
storage
what this line is saying is we're saying
we're going to create an object
of type simple storage contract
we're going to name it simple storage
with a lowercase s
and we're going to say this is going to
be a new simple storage contract and
we're saying this simple storage
contract takes no input parameters of
course if we deploy this contract as is
by going to our deploy tab
choosing the storage factory
staying on a javascript vm
deploying
scrolling down
we have this function that doesn't
return anything
so we're creating new contracts but we
can't really read where those contracts
are being created we'd have to look on a
block explorer like etherscan or
something
so let's make a way for us to keep track
of all the different simple storage
contracts that we deploy
let's put them in a list or in an array
so what we can do
is we can say
simple storage
array
of visibility public and we'll call it
simple storage
array
we'll initialize this symbol storage
array
and every time we deploy we create one
of these new simple storage contracts
we'll add it to our simple storage array
so we'll do simple storage array dot
push
and we'll push
this simple storage variable
so again i'm compiling or hitting
command s
delete that most recent contract
we'll choose the storage factory and not
the simple storage
and we'll hit deploy
now if we scroll down to our storage
factory
we have this blue button which stands
for our simple storage array
if we try to see what's at index 0 we
get an error of course because we
haven't added anything to it yet
if i click this create simple storage
contract
orange button here
now i've created a transaction that's
going to create a new simple storage
contract and push it onto our simple
storage array
now if i try to access the zerowith
index or the first index of this array
i'm going to get this address here
this is the address that this simple
storage contract was deployed to so
we've successfully deployed
a contract
to the blockchain from another contract
and this of course is really exciting
now we can actually do more than just
deploy the contracts we can actually
deploy contracts from another contract
and then call those functions as well
so let's create a new function where we
call
this store
function and we'll also create a
function where we call the retrieve
function from our storage factory so
we'll do function
storage factory store
we're going to shorthand it by saying sf
store we'll have it take unit 256
simple
storage
index
and a uint256
underscore simple
storage
number
we'll make this a public variable as
well in our little brackets here
and the reason i'm choosing a simple
storage index is because we're going to
choose which simple storage contract in
our list that we want to interact with
and then we're also going to pass a
simple storage number
to call
on the store function which of course we
need to pass a favorite number to any
time that you interact with a contract
you need two things
you need the address of the contract you
want to interact with and you also need
the abi for us we figured out that
we're going to push and get this address
from this simple storage array
we can get the abi or the application
binary interface from this import
we'll explain the application binary
interface a little bit more later
for now just know that in order for us
to interact with this simple storage
contract we can just do
simple storage
and then
we'll pass this simple storage the
address of that simple storage
contract
to get the address of that simple
storage contract
we'll say
grab the address
inside the simple storage array
at index simple storage index this will
return that contract that we want to
interact with
so we could even say
simple storage
simple
storage
equals simple storage
at that address in the array
once we get this contract we can then
call
any and all of its functions
so we could call
simple storage
dot store
this simple storage number
now if we compile this
we go to our deploy tab deploy the
factory
hit deploy
open this up we can see we have a couple
different functions here we of course
have our create simple storage function
which creates the contract and adds it
to our array
we now have this sf store
which stores
a number
to one of those contracts on this array
and then we have
a lens
into that simple storage contract
so if i create a simple storage contract
i can now store
on that zerowith contract on that first
contract any number that i want like 55.
of course i can't really see that 55
because we didn't add a retrieve
functionality we didn't add a way to
actually listen or read or retrieve that
favor number that we got
so let's add that now so
we'll create a new function
called
sfget and this will take a uint 256
simple storage
index
and as a parameter and we'll choose one
of these contracts on this array and
return
its favorite number
calling the retrieve function on that
contract
so since we're just going to be reading
state
this can be a public
view function
that will return
a uint256
to do this
we need to access that contract once
again
so we'll say simple
storage
simple storage
equals
simple storage
at that address
of
simple
storage array
at index
underscore simple
storage index
and we can return
return
simple storage
dot
we call this retrieve function
i'm just going to copy paste it so i
don't spell it wrong
simple storage we'll put the semicolon
here too
and here
now if we compile this go to our deploy
tab delete the most recent
choose the storage factory and hit
deploy
we can see we now has have an sfget
function
so let's go ahead
create a simple storage contract we'll
store a function on the zeroth contract
we'll store 55 as its favorite number
and we'll hit that
and then for s of get we'll see if we
can get
the favorite number of the zero with
contract
and we do indeed get 55.
awesome we can actually even refactor
this code to be a little bit simpler
here
we don't need to save
this simple storage contract is a
variable here we can actually just call
retrieve
on this whole section here
paste retrieve at the end
and just
return
like this
the same goes for our sf store
we can delete saving it as a variable
we can copy this dot store
paste it at the end here
and delete this as well
now we'll compile
delete the most recent
we'll deploy the storage factory
and if we go into it create a simple
storage
store the number 55
see what's at the zeroth index and we do
indeed see 55.
so
this is really cool this is a way for us
to actually deploy contracts and
interact with contracts from another
contract now to deploy a contract we do
need all the functionality of that
contract
imported however to interact with the
contract we don't need all of the
functionality we'll learn about
interfaces in the next lesson which will
allow us to actually interact with the
contract without having all the
functions defined and now i'm going to
show you something really cool now i'm
going to show you something really cool
simple storage has got a lot of really
cool functions and maybe i want all
these functions inside my storage
factory i want my storage factory to be
able to create simple storage contracts
and i want it to be a simple storage
contract itself
well what i can do
is my storage factory can actually
inherit
all the functions of simple storage
without me having to copy paste all
these functions and all these variables
over to storage factory what i can do
is i can do solidity's version of
inheritance
i can say contract storage factory
is of type
simple storage or is of contract simple
storage
and just by doing this line right here
my storage factory contract now will
have all of the functions and variables
of simple storage so it'll have
a store function a retrieve function an
add person function
a people array a name to favorite number
mapping it'll have everything because i
will inherit it with this is syntax
so if i go to my deploy tab now
[Music]
let's look at what our last storage
factory was
all we did to change this was add is
simple storage and we can see just the
four functions that we originally added
if i delete this now
if i save and compile the storage
factory let's go ahead and deploy
storage factory
if we open this up now
we can see
not only do we have all the functions
originally defined in our storage
factory but we additionally have all the
functions from our simple storage and
awesome you've completed the second
lesson we've learned about some
incredibly powerful tools here we've
learned how to import entire chunks of
code from other files into our files
we've learned how to do inheritance
we've learned how to deploy contracts
from our contract
and then we've learned how to interact
with different contracts from outside of
our contract well done now is a great
time to take a breath take a breather
and review what you've learned
the github repository associated with
this course also has all the code for
this lesson so let's jump into it so
we're back in remix now and we're going
to go to contracts and same as before
we're going to create a new file we're
going to call this fundme.sol
now same as last time we're actually
going to add this spdx license
identifier mit right at the top and then
we're going to choose our solidity
version
so we're going to go pragma solidity
and for this we're just going to do
greater than equals to
0.6.6
and less than 0.9.0
and great
this should look pretty familiar
now we're going to do contract fund me
and we're going to start working so what
again do we want this contract to do we
want this contract to be able to accept
some type of payment so let's create a
new function that can accept payment
we'll call it fund
so we'll do function
fund
public and we'll add a new keyword in
here called payable when we define a
function as payable we're saying hey
this function can be used to pay for
things when you call a function
every single function call has an
associated
value with it whenever you make a
transaction you can always append a
value
this value
is how much whey or gray or fini or
ether you're going to send with your
function call or your transaction
as we mentioned before
whey way and ether are just different
ways to talk about how much ether you're
going to send
so if we look at a way to ethereum
converter one each is
this much way
one way is the smallest denomination of
ether you can't break up ethereum into
anything smaller than one way this is
why when you're talking about how much
something costs everything always
defaults to whey or the smallest unit of
measure in ethereum so again for us to
test we're going to stick with the
javascript vm for now if we hit deploy
we get a new contract and this button is
now red it's red because it is a payable
function so now if i hit this fun button
[Music]
i can add
a value associated with it so what do we
want to do with this funding what do we
want to do when people send us something
well let's keep track of who sent us
some funding so what we can do is we can
create a new mapping between addresses
and value
so let's do a mapping
of address
to
uin256 which will represent the value
we'll make this a public mapping
and we'll call it
address to amount
funded
now in this fun function let's keep
track of all the people who sent us
money or all the addresses that sent us
some value
to do this we can use some keywords that
go along with every transaction so we'll
say address
to amount funded
of message.sender
equals
or
plus equals
message.value message.sender and
message.value are keywords in every
contract call and every transaction
message.sender is the sender of the
function call and message.value is how
much they sent
so whenever we call fund now somebody
can send some value because it's payable
and we're going to save everything in
this address to amount funded mapping
so if we deploy this now
in our javascript vm
we now have again a new view function
called address to amount funded and we
can even hit the drop down to see the
full name
now if i hit fund nothing's going to
happen right because my address is going
to be sending zero
in order for me to send something i have
to add some value along with my
transaction
so let's send for example one way
which is going to be equal to
1
1 2 3 4 5 6 7 8 9 this much way so
before i hit fund here if i copy this
fake account which is up here
and i put it in this address to amount
funded
it's going to return zero
but now if i add
1 1 2 3 4 5 6 7 8 9 in here
and we go ahead and hit fund now we've
now just called this fun function with a
value of one gray associated with it
so if i call
this address to amount funded now with
the same address i can now see
how much we've funded this smart
contract and we can even add more gray
we'll add
we'll add 11gway for example we'll call
fund and if we call this now we can see
that even more has been added when we
send our funds to a contract this
actually means that this contract
wherever this is deployed now is the
owner of this
amount of ether
so this is fantastic we now have a way
to fund our smart contracts now here's
the thing
in this smart contract in this funding
that we're doing we want to create a
minimum value for people to be able to
fund our endeavors which whatever they
may be we want to set some minimum value
here
and ether is great but for whatever
reason we want to work in usd or maybe
we want to work in some other token so
how are we going to get the conversion
rate from that currency to a currency
that we can use in this smart contract
well the first thing that we're going to
need to do to set this value is we're
going to need to know
what the eth
to usd
conversion rate is
because if i want to
accept ethereum as the token but i want
it in its usd currency well then i'm
going to need to know what that
conversion rate is so how are we going
to get this data into our smart contract
where are we going to get this data from
now remember how we talked about
blockchains being deterministic systems
and and oracles being the bridge between
blockchains and the real world well this
is exactly where oracle's come in when
we're talking about these systems you
know these blockchains they can't
connect to real-world events they can't
connect to external systems they can't
do external computation they're
intentionally these deterministic
systems these walled gardens so in order
for us to make this connection we need a
blockchain oracle we need some type of
network here now just to get a little
bit more technical for you if we look at
a blockchain a blockchain can easily say
one plus one
equals two and every other node can
easily verify this
however a blockchain can't easily say
okay let's all grab the same random
number because each node is going to get
a different random number they also
can't say hey let's make an api call
because if one node calls the api at a
different time another node calls it or
specifically an http get there could
potentially get very very different
results
and if another node tries to replay
these transactions by calling these apis
again
maybe 10 years in the future there's a
good chance that that api is going to be
depreciated
and they could be hacked they could be
malicious et cetera et cetera
the other reason that blockchains
intentionally can't make api calls is
because then they would be making
assumptions about the real world and
layer ones typically don't want to have
an opinion on any political or
geopolitical issue whereas an oracle
network on the other hand can make those
assumptions the other main thing we need
to talk about here is centralized
oracles being main points of failures if
you or i say hey i'm just going to be
the oracle i'm going to be the one to
put this data on chain we now have this
massive centralized point of failure
we've done all this work to make our
decentralized computation decentralized
and on chain but we ruin all the
decentrality by having a single point of
failure remember one of the whole
purposes of blockchain is so that not a
single entity can flip a switch and
restrict our freedom to interact with a
centralized oracle a single entity can
flip a switch and restrict our freedom
to interact with each other we also need
to get data from many different
decentralized sources or do any type of
computation in a decentralized manner
this is where chain link really shines
chain link is a modular decentralized
oracle infrastructure and oracle network
that allows us to get data and do
external computation in a highly civil
resistant decentralized manner it can be
as customizable as you want as you can
run with one node or many nodes or do as
many nodes as you like
now currently one of the most popular
features of chain link is their data
feeds or their price feeds we can even
go check them out
over at data
dot chain dot link
we can see a number of different price
feeds and the networks that are
providing the prices for these specific
pricing powers
we can see here by looking at the ui
there is a whole number of decentralized
different oracles returning data for
different price feeds this one for
example is fusd and it's also exactly
the price view that we're looking for
having a decentralized network bring
this data on chain and have it as a
reference point of definitive truth
allows users to all collaborate and use
this common good and it will be cheaper
more secure more efficient than anybody
even running their own centralized
oracle so these price feeds are
incredibly powerful additionally they're
being used by some of the top protocols
in the defy system right now
like synthetics which at the time of
recording is securing around 2 billion
sushi swap for leveraging trades set
protocol commodity money ave for
understanding the price of an underlying
collateral now this is an example of an
out of the box decentralized solution
that's already been packaged in the
decentralized manner for you to consume
and for you to use this makes going to
production a thousand times easier than
building everything yourself
however if you want to make api calls
and build your own decentralized network
you absolutely can with the chainlink
api calls
we're not going to go into that here
because using the chainlink price feeds
chainlink vrf keeper network and all
these other pre-box decentralized
services are going to make going live
and going mainnet a lot easier you can
always make a chain link http get call
as well we're not going to go over this
though because putting this into
production is a little bit trickier and
working with chainlink vrx if you ever
want to try them out by themselves you
can always head over to docs.chain.link
and head over to get the latest price
feed there's usually a remix button
actually that we can click and it will
kick us out to a remix edition with all
the code already ready to go for us if
we just hit this just right here this
will include all of our code which we'll
go into in a second
but let's go ahead and compile it
we're going to deploy it
to a real network here
this one looks like it's actually for
covin so we're going to go ahead and
switch to coven looks like i don't have
any covent ethereum so we're going to
grab
a covent faucet we can usually find
different faucets in the chain link
documentation
let's look up kovin here
there is a coven faucet here
it looks like in order for us to get
some covent ethereum here we have to log
in with github then we can add our
address in here and get the ethereum in
the interest of time i'm going to skip
ahead for me doing that
great it looks like i've got some covent
test that now being able to switch
between test nets is going to make you a
lot more effective as an engineer as
well because you're going to be able to
understand how each network actually
works so now we've compiled this
let's deploy this
again metamask is going to pop up
and let's go ahead and click to get the
latest price and we can see that this
function does indeed return the latest
price of ethereum
now you might be asking
why does this number look so big
well remember how we talked about whey
and gray and ether
well the reason that those exist is
because decimals don't work in solidity
so we actually have to return a value
that's multiplied by 10 to some number
so this value is actually 2614
times
10
raised to the eighth now the next
question you might ask is well why did
we work with this on a test net why
can't we do this on a local network and
the answer to this is because there is a
network of nodes looking at this test
net and delivering data onto this test
stem when you spin up a local network or
do a simulated vm there are no nodes
actually doing that we'll learn later
how to actually mock these interactions
and mock a chain link node returning
data onto our blockchain but for now
let's head back over to the contract
that we're working on so we can learn
how to implement this in any contract
that we ever want to another contract
called in this case called price feed
has a function called latest round data
which returns a lot of data it returns a
round id which defines how many times
this price feed has been updated it
returns a price which is the actual
conversion rate between the two assets
it returns a started at which defines
when this was last updated
it returns a time stamp and it returns
an answer in round don't worry about
answered in round for now if you want to
dive a little bit deeper into what these
rounds mean and what answered in round
means you can definitely check out the
chain link documentation and some of the
faqs to learn more now how do we
implement this data feed into our fundme
application well the first thing we're
actually going to need to do is we're
going to need to import the chain link
code
so we're going to do import
at chain link
contracts
source
v 0.6
interfaces
slash aggregator
v3
interface
dot soul
now let's talk about what this is
actually doing
oops looks like i spelt aggregator v3
interface wrong
all right great now it's actually
compiling
so let's talk about what imports
actually do
as we know an import will take whatever
code you're importing and stick it at
the top of your project so when we
import from at chainlink contracts we're
actually importing from the at chainlink
contracts npm package
we can look up at chain links contracts
in npm
and we can see and read more about this
repository
this links us back to the github which
will tell us a little bit more about
what's really going on if we follow that
import path that we got from the
documentation we'll end up on this file
in front of me now we have what's called
an interface you can see these contracts
don't start with the contract keyword
but they start with the interface
keyword they have the exact same pragma
solidity at the top but the main
difference is that you can see that
their functions aren't completed they
just have the function name
and its return type
now just to be a little bit more
explicit here i'm actually going to go
ahead and delete this import statement
on the top and replace it with that
interface code from github just to show
you exactly what's going on however if
you've already typed that at import
syntax feel free to leave it in there
and just remember that it's going to be
the exact same as me copy pasting the
interface code in our code here solidity
doesn't natively understand how to
interact with another contract we have
to tell solidity what functions can be
called on another contract this is where
interfaces are actually going to come in
similar to structs what we can do with
interfaces to find a new type so if we
copy all this code
from this section and place it at the
top of our code here
above where we're declaring a contract
we can actually then
interact with contracts that have these
functions
if we go ahead and even compile this we
can see this does indeed compile
correctly remember how we said before we
talked a little bit about abis well
interfaces actually compile down to
what's called the abi or the application
binary interface the application binary
interface
tells solidity what functions can be
called on another contract
we need solidity to know what functions
it can use and what functions it can
call other contracts with and if that
was a little bit confusing just know any
time you're going to interact with
another contract in solidity or smart
contract programming in general you're
going to need that contracts abi we'll
go into what these apis look like a
little bit later anyways to simplify it
interface compiles down to an api we
always need an api to interact with the
contract so how do we actually work with
this contract here to interact with an
interface contract it's going to work
the exact same way is interacting with a
struct or a variable let's define a new
function called getversion and we're
going to call this version function on
this other contract
so we'll start out doing function
get version
public
remember it needs to be a view since
we're just going to be reading this
state and even in the interface it even
defines it as a view returns
so we'll even grab
this whole bit right here
view returns unit 256. now the exact
same way we define variables and structs
we define working with other contracts
and interfaces so the first thing is we
name the type which in this case is
aggregator v3 interface
then we'd name the visibility but since
again we're inside of this contract
we're going to skip it then let's give
it a name
we'll call it
price feed since this aggregator v3
interface is going to be giving us a
price fee then we can do equals and this
is where we're going to initialize the
contract so how do we actually choose
where to interact with this contract
well we just type aggregator v3
interface and then we put in here the
address of where this contract is
located in order to find
where this fusd price feed contract is
located on the rink b chain we can look
at the ethereum price feeds chain link
documentation
it has a ton of different price feeds
and even more not price related data
let's scroll down to rink b
because again
on each different chain
the contract address that has all this
price feed information is going to be
different
let's scroll down and find fusd which is
right here
and we'll copy it
and we'll paste it into here
now what is this line saying
it's saying that we have a contract that
has
these functions defined in the interface
located at this address if that's true
then we should be able to call
price feed
dot
version
and we should be able to return it
whoops looks like we forgot to add
those here
and we need a semicolon here
i hit ctrl s or command s compiled it
looks like we're compiling successfully
and we do need to deploy this on a test
n
remember this address here is located on
an actual test tent it's located on an
actual network it's not going to be
located on our simulated chain here so
we do need to deploy this to injected
web 3. we do need to deploy our contract
to rink b because the rink b chain has
this address
we'll learn later on how we actually can
work with a simulated chain and work
with these price feeds but that's much
later in this course so let's go ahead
and save
we'll deploy
make sure we're on injected web 3.
now we can go ahead and hit deploy
metamask is going to pop up per usual
confirm
we're going to get a transaction link to
etherscan showing us our contract
and once it actually is confirmed we can
see we have our contract right here now
we have our familiar functions with one
additional function
we have our fund button which is red
because it's payable we have our address
to amount funded mapping which is blue
because it's a view
and we also have this get version button
that's also blue if we go ahead and
click it we can see that the version of
our aggregator v3 interface is version
3. this is the third version of the
aggregator interfaces hence the name
aggregator v3 interface so we just made
a contract call to another contract from
our contract using an interface this is
why interfaces are so powerful because
they're a minimalistic view into another
contract so this is great we have a get
version function but this still isn't
the function that we want we want to
call the get price function which if we
look at our interface we can see there's
a latest round data function that
returns
an answer this is the function that
we're going to want to call on this
contract so let's go ahead and make a
function that calls that instead
so we're going to do
function
get price
public
view
returns
uint 256.
uh oh
this latest round data function though
returns
five variables so how do we actually
work with that well let's find out to
work with this contract we're gonna do
the exact same thing
we're gonna do aggregator v3 interface
because this is the type of the contract
price feed
equals
aggregator v3 interface
we'll do this same address in here
because this is the fusd address
then we'll do price feed
dot
latest round data
now since this is going to return
five different values
we can actually have our contract also
return these five different values
we can copy paste like this
and literally do
this
these five values equal price feed that
latest round data
and you can see
that even compiles correctly let's
adjust the formatting a little bit here
so it looks a little bit nicer a tuple
is a list of objects of potentially
different types this is the syntax for
getting a tuple we can define several
variables inside one of these tuples
although our compiler is going to give
us some warnings it's saying unused
local variable because we're not
actually using these for anything we'll
come back to this
now we can go ahead and do return
and we can pick one of these variables
that we want to return answer is going
to be the price so we're going to do
return
answer but uh-oh we're going to run into
an error return type argument in 256 is
not implicitly convertible to expected
type answer is an int 256 and we want to
return a uint 256 so how do we rectify
this we can fix this by using what's
called typecasting if we just return
answer we're going to be returning the
wrong type however integers and solidity
are really easy to cast into each other
so we can just do uint 256
and wrap it around this answer
and then compile and save that instead
as you can see now our compiler is happy
because we've changed this answer into a
unit 256
awesome so now this get price should
return the latest price of ethereum in
terms of usd let's go ahead and deploy
this new contract with this new function
so same thing we're going to come to our
deploy section
hit the deploy button up remember we got
to go to the fundbean.sol
let's deploy it
confirm with metamask here
and let's scroll down to our newly
deployed contract
as you can see we have our get version
function which still works exactly the
same but we have a new function too
called get price and this should return
a uint 256 answer let's go ahead and
click it
amazing we've actually returned an
answer now again if you're a little
confused on why this number looks so big
you have to remember that this actually
has eight decimals we could call this
decimal's function on the contract to
learn that one two three four five six
seven eight and we know that the current
price of ethereum in terms of usd
is two thousand four hundred and
eighty-two awesome so now that we have
the price we can actually get the
conversion rate but let's clean up this
function a little bit before we go on up
there as you can see one thing that the
compiler is complaining about is we have
a lot of unused local variables
but latest round data returns
five different variables
so how do we actually return the five
variables but make our compiler happy
with us well we can actually just return
blanks for each one of these sections
with commas in between each other to say
hey there is a variable here but we're
not going to use it
this will also make our code look a lot
cleaner
because now this function's a lot
smaller
we say
something's here we're ignoring it
in 256 answer we're going to use some
things here ignore it something here
ignore it and ignore this too and we can
even test this out by compiling it
deploying it
checking on rank b
scrolling down
hitting this
and hitting get price and you can see
indeed it's the exact same as before
awesome so now we're all done cleaning
things up right not quite yet
see the other thing that's really
annoying here we have this massive chunk
of code at the top
that is probably a little redundant
there's a good chance that a lot of our
contracts are going to want to use this
aggregator v3 interface so let's just go
ahead and add that at chain link
contract syntax back in because it's
going to look a lot cleaner here and do
at chain link
contracts if you ever get a little bit
confused with what you should be
importing to work with their contracts
we can see right in the documentation at
the top this at syntax is what this is
going to use
now you can also go ahead and browse
that npm package of at chainlink
contracts see what other applications
are in there and what other files are in
there
or you can just peruse around the github
now the third way we can actually do
imports is we can import from contracts
that are in the same file system as our
contracts well awesome our contract is
starting to look more and more put
together now one other thing that i
usually like to do with these is i
usually like to put everything into the
gray
way standard so as we saw
this get price had eight decimal places
however
the smallest unit of measure aka whey
if we look at it has 18. one two three
four five six seven eight nine ten one
two three four five six seven eight
so typically in these i like to try to
make everything have 18 decimals as well
you don't have to do this and it'll save
some gas if you don't but i usually like
to multiply everything so that
everything has 18 decimal places so
since i know this has 8 i can just do 1
2 three four five six seven eight nine
ten
and now this will return
the price with eighteen decimal places
instead of ten now we have the price of
ethereum in us dollar which is fantastic
so we could set the price of our funding
function to anything that we want here
for example let's say 50
we could convert whatever value that
they send us to its us dollar equivalent
and see if it's greater than or less
than fifty dollars
all we have to do is make a new function
that converts that value that they send
to its us dollar equivalent so we could
do function
get conver
generate
and it will take a u 256
f amount let's get this out of the way
for the rest of this
it'll be a public view function since
again we're not actually going to have
it make any state change
we'll do returns you want 256
and then in this function
we can do uint 256
f price
equals
get price
and we can call
this get price function up here
now we have the price in here
what we want to do is we want to convert
whatever value that they send
as f amount let's say they send one way
or again that's going to be this much
way
what how do we convert this
to fusd
well
we can now do unit 256
s
amount
in usd
equals
this f price
times
the f amount that they sent
this is actually going to
result in a much bigger number than
we're looking for and then of course
we're going to return it
let's test this out and see why we have
to do one more thing here
so let's again
fund me we'll deploy
rank
b we'll scroll down and we have this new
function called get conversion rate
let's grab this one gray and put it in
here whoa
this seems like it's a really big number
we're saying that
one gray
is equal to one two three four five six
seven eight one two three four five six
seven eight nine ten
this many dollars
now i don't know about you but i don't
think the price of even one ethereum is
that many dollars maybe in the distant
future but definitely not right now the
reason that it's off is we have to then
actually divide by
this number the reason that we have to
do this is because both f price and f
amount
have an additional
10 raised to the 18th tacked on to them
so now we have to divide it out in order
to get the right number
so we're going to compile
compile
deploy
confirm
we can scroll down
and now let's try this one way
we'll get the conversion right here
and we can see we get a number that
makes a little bit more sense now
remember this has 18 decimals as well so
the real number is 1 2 3 4 5 6 7 8 1 2 3
4 5
6 7 8 9 10.
and we know that this number is actually
accurate because we can go ahead and
pull up a calculator
pop that into here
and we know that this is one way in us
dollar
if we get the conversion rate
we're saying that this many gray equals
one each
so we can check it back by multiplying
this number by that and we see that we
do actually get the price of one
ethereum in us dollar
so our math here checks out
awesome now since we're on the topic of
math i do want to talk briefly about
some of the pitfalls of solidity
especially when it comes to math prior
to solidity 0.8 if you added to the
maximum size a uint number could be it
would actually wrap around to the lowest
number that it would be and in fact you
can even demo this with a contract here
now you don't have to follow along with
this contract but just watch to see the
example we're going to call this
overflow
dot sol
now in here we're going to add all kind
of the normal stuff
contract
overflow
and we're going to add a function
called
overflow we'll make a public
view and we'll have it return a uint 8.
i'll show you why in just a minute a
union 256 is a really really big number
and it's hard to kind of imagine going
over the maximum cap of a u and 256
but a uint 8 is a lot smaller with the
maximum number actually being 255. so if
we create a uint 8 and we call it
big
equals 255 and then we just do return
big
what do we think we're going to get here
for this we can go ahead and use
javascript vm because we're not
interacting with any other contracts
let's deploy this
and we'll see in our contract if we call
overflow now we're just going to get
255.
however what happens if we add 1 to this
number or try to add 1 to this number if
we do it just like this solidity
actually knows that there's an issue
here and says hey
try not to do this
but if we typecast this as a uint eight
solidity gets a little bit more confused
and goes ahead and lets us do this
now what do we think big is going to be
it should be 256 right
but big is the uint 8 and this is the
maximum size that it could be so what
happens when we deploy this
we look down
we actually get zero
what happens if we do 100 and we deploy
that
we actually get 99
and this is because integers can
actually wrap around once you reach
their maximum cap they basically reset
this is something we need to watch out
for when working with solidity if we're
doing multiplication on really big
numbers we can accidentally pass this
cap luckily as a version 0.8 of solidity
it actually checks for overflow and it
defaults to check for overflow to
increase readability of code even if
that comes a slight increase of gas
costs you can use this unchecked if you
want to have it keep that wrapping
functionality so just be aware if you're
using a lower version than 0.8 you're
going to have to do something to make up
for this and we could write a whole
bunch of code here basically to check
all of our math
or we could just import something called
safe math from another package
similar to how we imported chain link we
can go ahead and
import a package called
safe math
from a tool called open zeppelin
now open zeppelin is an open source tool
that allows us to use a lot of already
pre-built contracts
we can go ahead to the documentation and
go to their utilities and see safe math
and they even have a little sticker here
saying safe math is no longer needed
started with solidity 0.8 safe math is a
tool and a way for us to avoid some of
these problems with doing math and
solidity now i'm not going to spend too
much time on the contracts that actually
fix this but we can actually import
right from the chain link directory as
well
a solidity file called safe math chain
link and what we can do is right after
our contract
we can do using
safe math chain link
for
uint256
and what this will do
is it will use safe math chain link for
all of our unit 256
and safe math chain link doesn't allow
for that overflow to occur libraries are
really similar to contracts except that
they're isolated code that can be run in
a reusable context
in this case we're attaching the safe
math chain link library to uint256 so
that these overflows are automatically
checked for just keep in mind if you're
using anything less than 0.8 you're
going to want to use some type of safe
math just to check for your overflows
now this is for those of you who are
familiar with safe math and integer
overflows and underflows we are not
going to be calling the functions that
safe math provides us like div add mole
you know all those functions simply
because in 0.8 moving forward we no
longer have to use those and we can just
use our regular operators like plus and
minus so this is great our contract is
coming along really well we now have a
way to get the conversion rate of
whatever f is sent and turn it into us
dollar
now we can set a threshold in terms of
us dollar but how do we guarantee that
whatever amount that the users send when
they call fund is going to be at least
fifty dollars well first we might want
to set a minimum value so we can do unit
256
minimum usd
equals
let's say 50
and again since we're using everything
in way terms we want to then multiply
this by 10
raised to the 18th
and just want to take a pause for a
second because this line is actually
wrong this should be raised to the 18th
so this line should really look like
this where it has the double star so
apologies the rest of this has that
single star but it should be the double
star here if you do have the single star
though the rest of the contract will
still work fine so this will be the
minimum value it'll be 50
times 10
raised to the 18th so that everything
has 18 decimals now that we have a
minimum amount how do we actually make
sure that this minimum amount is met in
the value that they send us well if
you're familiar with if statements we
could do something like if message.value
is less than minimum usd
then
revert
or
we could do something a lot easier and
better practice and much cleaner we do
what's called a require statement when a
function call reaches a require
statement it'll check the truthiness of
whatever require you've asked so in our
case the converted rate of message.value
needs to be greater than or equal to
our minimum usd
this line
says that if the conversion rate of
message on value to usd if they didn't
send us enough ether
then we are going to stop executing
we're going to kick it out we're going
to say hey this doesn't count and we're
going to do what's called a revert we're
going to revert the transaction this
means that the user is going to get
their money back as well as any unspent
gas and this is highly recommended we
can also then additionally add a
revert error message something like
you need to spend more eath
so now let's try this out as we saw one
way
is going to be way less than fifty
dollars so if we send one way along with
this fund contract call it should kick
out and say you need to spend more eth
so let's actually try this let's go to
the deploy tab
we'll get rid of our overflow
we use injected web 3 because again we
are working with the chain link
aggregated contracts that are on chain
we're going to move to
fund me
and we're going to hit deploy
metamath's going to pop up and we're
going to hit confirm
now if i try to hit fund
let's see what happens we're getting a
gas estimation
failed since gas estimation error failed
with the following message
execution reverted you need to spend
more eth
so
the contract isn't even letting us make
the transaction we can go ahead and try
to send the transaction but here's
what's going to happen
on ether scan
once this goes through
you can see that once this transaction
finished we got this status fail with
error you need to spend more eth we
don't want to force these transactions
to go through if we look at our metamask
we can even see this failed bit here
so whenever you see these gas estimation
failed errors usually that means
something reverted or you didn't do
something that was required however if
we go to value here and we spend a lot
more
let's say
0.1 ether
which if we take out our calculator 2500
times point one it's going to be 250
dollars this should easily be well and
beyond past our 50 threshold
so let's add 0.1 ether remember we got
0.1 by adding it in the converter and
grabbing the way again the way is the
smallest denomination now if we change
this to way and hit fund this should go
through we're gonna hit fun now you'll
see men and mass pops up because
metamask goes oh yeah this transaction
isn't going to revert and that's what we
want so we can go ahead and hit confirm
and now we'll finally have sent some
funding to our contract
now that this is confirmed we go ahead
and grab our address here
pop it into our address to amount and we
can see that indeed our funding has gone
through
now we can be part of this crowdsourcing
application with our minimum value which
is fantastic awesome great job
awesome so now we can fund this contract
with a certain minimum usd value in this
case it's going to be 50
now you'll notice though that right now
we don't do anything with this money so
we're going to fund this contract
however that's it and we don't have a
function in here to actually withdraw
the money so there's no way that even
though we just sent this contract some
money there's no way for us to get it
back so how do we fix this well we can
add a withdraw function in here so let's
go ahead and add that
function
withdraw
and this is also going to be a payable
function because we're going to be
transferring eth
we'll make this public
and we can do
message
dot sender dot transfer transfer is a
function that we can call on any address
to send eth from one address to another
this transfer function sends some amount
of ethereum to whoever it's being called
on in this case we're transferring
ethereum to message.sender so all we
need to do now is define how much we
want to send well we're going to send
all the money that's been funded so to
get all the money that's been funded in
this contract
we can do address
this
dot balance
now there's a couple of special things
going on with this line
first we're saying address of this
this is a key word in solidity whenever
you refer to this you're talking about
the contract that you're currently in
and
when we add address of this we're saying
we want the address of the contract that
we're currently in whenever you call an
address and then the balance attribute
you can see the balance in ether of a
contract so with this line we're saying
whoever called the withdraw function
because whoever calls the function is
going to be the message.sender
transfer them
all of our money so let's go ahead and
try this let's deploy fundme
and now let's fund this with a lot of
ether so that we can see it we'll fund
it with one whole ether
so that we can see it go into the
contract and get pulled out of the
contract
we'll hit the fun
button and you'll see we're sending one
whole ether into this contract
now if we look at our balance it's gone
down from 17 to 16. or if you're still
at 18 it went down from 18. so let's try
to get it back
if we call this withdraw function now
confirm
once this transaction goes through we
should get all of our ether back
let's look at our metamask and boom
indeed we have got all of our eth back
however looking at this contract we can
see that hmm well maybe we don't want
anybody to be able to withdraw all the
funds in this contract that seems like
it might be a really bad idea maybe we
only want the funding admin to be able
to withdraw funds so how do we set this
up in a way that only the contract owner
can actually withdraw funds well we
learned before
that the require function can actually
stop contracts from executing unless
some certain parameters are met we can
do the same thing here with require
message.sender
equals
the owner
but we don't have an owner to this
contract yet so how do we get an owner
to this contract the instant that we
deploy it well we could have a function
called create owner but what happens if
somebody calls this function right after
we deploy it
well then we wouldn't be the owner
anymore
so we actually need a function to get
called the instant we deploy this smart
contract and that's actually exactly
what the constructor does so typically
at the top of your smart contracts
you'll see a constructor
and this is a function that gets called
the instant your contract gets deployed
you don't even need to do add function
here we can literally just call it
constructor
because it's what constructs the smart
contract so we'll make constructor
public and whatever we add in here will
be immediately executed whenever we
deploy this contract so one thing that
we could do
is we could have an owner be set the
instant we deploy the smart contract so
in the top we could add address
owner
and in our constructor
we could say owner equals message.sender
because the sender of this message is
going to be us it's going to be whoever
deploys this smart contract we can even
test this out in the javascript vm to be
a little bit quicker because we're not
actually going to be calling the fund
or the getprice function for now oops
let's also make this public so that we
can interact and see this owner variable
so now if we go to fund me we deploy
this in the javascript vm we should be
able to see who the owner of this
contract is and it should be our address
because this constructor function should
have been immediately called the instant
that we deployed the smart contract
awesome we can see the owner of this
smart contract is indeed our wallet
because remember we're working with the
javascript vm our wallet is these fake
wallets that they kind of give us
we can even try this with an injected
web 3
with deploying this
and the owner
should be this
ox 757 etc address
let's go ahead and look at fundme see
the owner and we do indeed see the owner
is us okay great
now we have an owner
we can go down to our withdraw function
and use that same require
so we can call
acquire
message.sender
equals equals
owner equals equals is the way that
solidity understands true false we're
saying that message.sender has to equal
owner now let's go ahead and try this
and we'll try with the javascript vm
again for speed reasons
let's deploy this funding
and if we go down here
we try to call the withdraw function and
it looks like it is successful because
currently
this is the address that deployed the
contract and it's also the address that
is calling withdraw
however
if we switch to a different account
and call withdraw you'll see
that remix actually freaks out down here
it says uh oh something wrong happened
and this is essentially the require
statement kicking out if you want to try
it with injected web 3 as
well can absolutely do that too and
remember the way to switch accounts in
metamask is to either create a count
right here or just switch like this
and then we'll connect with account two
so if i try to withdraw
from this
second account
that didn't call the contract and i hit
withdraw now
it's going to give us gas estimation
failed because the required statement is
going to kick out but again if we switch
back to account 1
and we call withdraw
metamask is going to pop up and it's
going to allow us to withdraw now
obviously there's nothing in this
contract right now so we're going to
withdraw nothing but we can still call
it it's going to do message.transfer
0.
so this is great
we can now require this withdraw
function is only callable by the owner
now what if we have a ton of contracts
that want to use something like this
they require the message.sender to be
some owner or maybe it's more
complicated than this is there an easier
way to wrap our functions and some
require or some other executable well
this is where modifiers come in we can
use a modifier to write in the
definition of our function
add some parameter that allows it to
only be called by our admin contract
modifiers are used to change the
behavior of functions in a declarative
way let's create our first modifier
we'll call it modifier
which is a keyword
only owner
and we'll add this require statement in
here
require message.sender equals owner
then after this we just add an
underscore and a semicolon
what a modifier is going to do
is it's going to say hey before you run
this function do this require statement
first and then wherever your underscore
is in the modifier run the rest of the
code
so we could also do a modifier where the
underscore is up here and then this is
afterwards but but we want to run the
require first
so now what we can do
is we can make this function withdraw
payable
only owner public
and what's going to happen
is before we do this transfer we're
actually going to check
this modifier we're actually going to
run this require message.sender equals
owner and then again where this
underscore is that's where we'll add the
rest of the function
so again
for speed reasons and since we're not
actually going to be interacting with
the chain link data contract we can go
to javascript vm
switch to funding
deploy
and we can call withdraw
obviously we can call withdraw from our
account but if we switch accounts and
try to call withdraw
we're going to get an error which is
perfect because that means our modifier
is working correctly
awesome now we have a fantastically
succinct fund me contract here
the only thing that we're really missing
is that when we withdraw from this
contract we're actually not updating our
balances of people who funded this
so even after with we withdraw this is
always going to be the same so we need
to go through all the funders in this
mapping and reset their balances to zero
but how do we actually do that we can't
actually loop through
all the keys in a mapping when a mapping
is initialized every single key is
essentially initialized now we obviously
can't go through every single possible
key on the planet
however what we can do is create another
data structure an array something we're
already familiar with so let's go ahead
and create a new funders array that way
we can loop through them and reset
everyone's balance to zero we'll do an
address array
because it's going to be an array of all
the funders addresses
we'll make it public
and we'll call it
funders
now when somebody funds a contract
what we're going to do is we're going to
do funders
now whenever a funder funds this
contract we can go ahead and push them
onto our funders array
so we can do funders
dot push message dot sender
now if somebody funds multiple times the
funders array is going to be a little
bit redundant but we're going to ignore
that for now now that we have an array
of funders when we withdraw everything
we're going to want to reset this to 0.
when we withdraw everything we want to
reset everyone's balance in that mapping
to 0. so we're going to do what's called
a for loop a for loop is a way to loop
through a range of numbers to do
something so we're going to say
4
you and 256
funder index
equals zero because we want to start
with the zeroth index
we're going to give it a max size to go
to we're going to say the funder index
has to be less
than funders dot length
dot length is how we get the length of
our array
and then we're going to say funders
index
plus plus this means that we have an
index variable called funder index
and it's going to start from zero
this loop is going to finish whenever
funder index is greater than the length
of the funders
every time we finish a loop we're going
to add one to the funder index that's
what that funder index plus plus does it
adds one to the funder index and every
time whatever code is in this for loop
executes we're going to restart at the
top and all we're going to do in here is
we're going to grab
the address of the funder
from
our funders array
funders
so the funder
at the index in our funders array
we're going to use this
as the key in our mapping
so we're going to take
address to amount funded
of funder
and we're going to set it equal to zero
so now our mapping is going to be all
updated to people having xero funded in
there
we do have to do one more thing as well
we have to reset our funder array as
well
now there's a couple ways to do this but
a really easy way is just to
set funders equal to a new array so we
could do funders
equals a new
blank
address array
so all right it looks like we've got
everything in here we need right away
when we deploy this we are set as the
owner
we can allow anybody to fund whatever
public good that we're doing
and they have to fund it with the
minimum usd value that we actually set
whenever they fund we'll keep track of
how much they're funding and who's been
funding us we can get the price of the
ethereum that they send in the terms of
usd
and we can convert it to check to see if
they're sending us the right amount
we have our only owner modifier so that
we're the only ones who can withdraw
from the contract and when we do
withdraw everything from the contract we
reset all the funders who have currently
participated in our crowdsourcing
application
awesome let's see if everything works
end to end
so we're going to go to fundme
we're going to deploy it
we're going to confirm from metamask and
remember if you're ever confused about
what's going on or or something weird is
happening in your transactions or your
deployments you can always go into
etherscan and read more about your
transaction and what's going on
now that our transaction has been
deployed let's go ahead and just take
inventory as what's going on
we have our owner
which is our address right here
we have the aggregator v3 interface
version which is version 3 which we can
kind of ignore
we have the price of ethereum in terms
of usd
with 18 decimals instead of 8. we have a
function that allows us to get the
conversion rate of any ethereum amount
to its us dollar equivalent
we have an array of funders which right
now starts out as empty
we have a mapping of addresses which
also right now starts out as empty let's
go ahead and try to fund this contract
we'll use way just that we're always on
the same page
and we'll fund it with 0.1 away
remember everything has 18 decimal
places so if we want to do 0.1 we just
do 17. so we can do one one two three
four five six seven eight one two three
four five six seven eight nine and
that'll be 0.1 ethereum now we can go
ahead and hit fund
and we're going to send 0.1 eth to this
contract
great so if we look at the zeroth index
of funders we can see that indeed
we have funded this contract
let's even have
our second account fund this contract
so all we got to do is switch
to this contract in metamask
we can go ahead
and put point one eth back in here
for value
and hit fund
now as you can see we're deploying this
from account two
let's go ahead and hit confirm
funder at index zero is going to be our
admin and the funder at index one is
going to be our second account
and if we go ahead
and we add
this funder in here we can see we've
indeed sent point one ether with this
account if we go back to our count one
and put this in here
we can see that that address also has
0.1 ether
fantastic
so let's try to be malicious let's try
to have account number 2 actually
withdraw all the funds in here
let's hit this withdraw function
uh-oh
the transaction has failed we're
relentlessly malicious we want to send
this transaction regardless so even
though i'm not the admin of this
contract i've gone ahead and still tried
to send those withdrawal so what happens
now
we can see that remix is saying hey
something went wrong
and again if we look at ether scan we
can see that there is a fail here since
in our modifier we didn't give a reason
here
nothing shows up but we could have
always put a reason in there and
something would show up
so all right let's go ahead back to the
actual admin
and now let's try to withdraw everything
so if we hit withdraw now
we can go ahead and confirm what should
happen is everything in here should be
back to zero and this array should be
back to zero as well and if we watch our
address we can see it literally just
went from point four to point six
because it got point one from the
original funding that this account put
in
and the 0.1 that our second account put
in
so now if we look at funder 0 we can see
it actually errored because it is now a
brand new array and there is nothing at
index zero if we try to see how much
this address now is funded it's back
down to zero awesome you've now learned
how to deploy a relatively simple yet
effective crowdsourcing application
where users can fund and an admin can
withdraw those funds to go spend them on
things
now we've been working with remix so far
to start our smart contract in our
solidity development journey remix is an
incredibly powerful what's known as a
web ide or an integrated development
environment and in my opinion remix
should always be the starting ground for
anybody looking to start their smart
contract journey because it is a
wonderfully friendly way to really show
what's going on behind the scenes and
it's really easy to see everything we're
doing with ethereum with chain link and
with our smart contracts now it does
have some limitations though it's really
hard to integrate other parts of
different projects it has some limited
support for testing or custom
deployments it's a little tricky to save
files locally you need an internet
connection to actually interact with it
and it doesn't have python so in order
for us to deploy test and automate
everything about our smart contract
development cycle we want to connect our
solidity and our smart contracts with a
more traditional programming language
like python this way we can customize
our entire development environment in
any way that we like we're first going
to teach you all how to work with what's
known as web3.pi which is an incredibly
powerful python package for doing
everything that we want to do with smart
contracts then once we learn some of the
basics of web3.pi then we'll move on to
browning which is a smart contract
development framework built on top of
web3.pi which makes our lives even
easier however it's still really
important to learn web3.pi first because
this will teach you what's going on
behind the scenes of brownie
now for the rest of this course i'm
going to be working with visual studio
code which is an incredibly powerful
text editor that will give us a lot of
formatting and a lot of really nice
tools to work with deploying and
interacting with our smart contracts if
you've already got vs code and python
and your entire coding setup set up the
way that you like it feel free to use
the timestamps in the description to
skip ahead to the next section you'll
often hear people referring to this as
vs code or visual studio code but just
to point out this is not what you're
looking for right in front of you here
visual studio is a different application
make sure you're on visual studio code
if you want to be a total hardo and just
work with vim or emacs or whatever else
you want to do you absolutely can but
i'm going to go through setting up
visual studio code the way that i like
it and if you guys want to follow along
i highly recommend it because it's going
to make your life a lot easier there's a
link to download visual studio code in
the github repository basically all you
have to do is come to the site right
here and you can hit this big download
button it should recognize what
operating system that you're on be it
windows be it mac or some other
operating system and if it doesn't you
can go ahead and hit this little drop
down and pick one there so let's go
ahead and download visual studio code
and open it up
awesome once you've downloaded visual
studio code this is approximately what
you should be seeing
there's a fantastic getting started
section here where if you're brand new
to vs code and you want to learn a
little bit more quickly you absolutely
can and we have some links as well in
our github repository giving you a crash
course in vs code if you want to learn
more let's set this up though so it's
going to be really friendly for us to be
doing our smart contract development
here so first we want to go to this
extensions tab it looks like these
little blocks thing right here
and first we're going to look up python
and you want to install this python
extension right here this is going to
make our lives a lot easier for
interacting with python and doing a lot
of things with python
then you're going to want to go ahead
and download this and install this
solidity extension this is going to make
formatting our solidity a lot easier now
we want to download python if you
haven't already so go ahead to
python.org
let's go to downloads and it should
recognize what operating system that
you're on and you can just go ahead and
hit the download button and then follow
the steps to download this i've already
got it download so i'm not going to walk
through this
okay great now that we have python
installed one of the other amazing
things about vs code is you can actually
open a terminal up inside a visual
studio code the way you can open your
own terminal if this is your vs code
you can go over on this top bar to
terminal
and select new terminal
and you'll see something that looks like
this
it might be a bash it might be a zch it
might be a powershell there's a lot of
different types of terminals that you'll
be able to see by looking right here we
can now test to see if python is
installed correctly if we type in python
space
dash dash
version
we should get something that looks like
this the exact version of python doesn't
really matter here but ideally you're at
least on python 3.8 if python dash
version doesn't work you can also try
python
3-version now if neither one of those
works we actually have a number of
troubleshooting tips in the github
repository for this course and
oftentimes a quick google search on
whatever error that you have you'll get
a link which will lead you to the answer
but if that google search doesn't lead
to the answer then just go ahead and
drop an issue or conversation associated
with your issue on the github repo
associated with this course in
particular there are a couple of common
errors that i've definitely seen a
number of times so if you see an issue
on your instance that matches something
on the screen here definitely 100 be
sure to check out those troubleshooting
tips sometimes just installing some of
these applications is really the hardest
part of doing the entire coding journey
here so please make sure you have python
and vs code installed correctly before
moving on and don't be discouraged if
this doesn't work exactly the way that
it should right away now if you're on a
mac you can actually hit control back
tick and it will toggle back and forth
between having the terminal open and
closing it i find this really helpful
and i use it all the time instead of
hitting
the buttons a key tip for productivity
is going to be using keyboard shortcuts
instead of clicking around all the time
you'll be much faster okay great we have
python installed we have python and
solidity extensions of visual studio
code installed let's start working on a
new project so in our terminal so in our
terminal we can create some folder i've
already created a demos folder here
you can create one as well if you'd like
by doing mkdir
demos
since i've already done it the file
already already exists
and then cd into demos
you can type clear or if you're on a mac
command k to clear the terminal now
here's what we're going to be doing
we're going to be working with
simple storage again the exact same
contracts but instead we're going to be
using web3.pi
so we're going to make a new directory
inside of our demos folder slash
directory called web3
pi
simple storage
and we're going to cd
into this new
folder right here now again all the
completed code is going to be in our
github and there's going to be a link to
everything that we do in this folder in
this github so you can always refer to
that if you get lost and the next thing
that we want to do is we want to have
our visual studio code know that we're
in this folder so we can go ahead and
click this files icon and hit open
folder
and i'm just going to go to this web 3
pi simple storage and hit open and
another vs code will actually pop up we
can see on the left hand side here
we have a folder this will show all the
different files and folders in our web 3
pi simple storage directory let's go
ahead and create a file
dot sol we can right click on this area
and select new file and do
simple
storage
dot soul and then we can go back to our
simple storage dot soul in remix copy
everything and then paste it into here
if you don't have it up remember you can
always refer back to the github
repository which will have it in there
for you awesome now we have our solidity
in its own file called
simplestorage.soul you'll notice that
some of the words are actually
highlighted different colors this is
known as syntax highlighting and it's
due to the fact that we added the
solidity extension in it makes reading
this code a lot easier now this file is
in here we'll see that we have this
little dot here
whenever you see this little dot this
means that your vs code file isn't saved
so we want to always save it otherwise
when we compile or we go to write a
script things might not work correctly
so we can save it by going up to file
and then selecting save or again you're
going to want to learn how to do the
keyboard shortcuts because you're going
to want to hit save often for mac it's
command s and for windows it's ctrl s
now the other thing that you'll see is
you get this red line here this is vs
code's way of telling us it thinks that
there's an error at this position so
this is really just the extension being
a little bit confused here and we can
safely ignore this and normally when i'm
coding i do just ignore it we're often
going to be flipping back and forth
between compiler versions so oftentimes
this isn't really a helpful warning here
but if it is really bothersome you could
right click it and do something like
solidity change global compiler version
or we can go to code
preferences
settings
let's close this so we can see some more
things in here we'll look up solidity
and we'll come to this solidity
extension config what we can do then is
scroll down
and we can see solidity compile using
remote version this will allow us to
choose what version we want to compile
with if we do 0.6.0
and hit save
and go back to simple storage you'll see
the red line is now gone while we have
this up another really helpful piece
that we can do here is we can add what's
called a formatter so if we scroll down
to solidity formatter you'll see that
this enable slash disables the solidity
formatter we can go from none to
prettier then we'll also look up format
on save and we want to make sure we have
this editor format on save check marked
what we can do then is we can come over
to simplestorage.sol
and
maybe i've got some bad formatting in
here we'll move over favorite number
string name and put a whole bunch of new
spaces in here or something
now if i hit save it automatically
reformats our file to look a lot nicer
so to recap we want to turn on format on
save and if you get issues with a red
line under pragma solidity you can just
change the compiler version in your
settings here now while we're in here
we're also going to go ahead and set up
our python formatting as well
so the first thing that we're going to
do is we're going to install the black
python formatter so we're going to open
up our terminal here
and whenever you install python it comes
pre-installed with this package called
pip to check to see if you have pip
installed correctly run pip dash dash
version
now we can install the black formatter
by running pip
install
black
i already have it installed so it's
going to be pretty quick for me
then we'll come to our settings
and we'll look up
python
formatting
and we'll scroll down
to python formatting provider you might
have autopet bait or none in here you're
going to want to change it to black
this way whenever we save our python
files now they will also get
automatically formatted to be very
readable and really nice and just to
note for my demos in solidity i don't
always have format on save for solidity
i do have format on save for my python
but i'm still going to highly recommend
you have format on save for both your
python and for your solidity anyways so
how are we going to actually deploy this
well this is where our python is going
to come into play
let's go ahead and create a new file on
the left here
and we'll call it
deploy dot pi now let's go into this
deploy.pi file and let's start actually
figuring how we can deploy this in
python and this is the part of the
course where we start using python here
if you're unfamiliar with python or a
little bit weaker on python there is a
fantastic free code camp course that
goes through all the basics of python if
you want to learn more i definitely
recommend checking it out however we are
going to walk you through all the
scripts that we write anyways so don't
be afraid to just jump in and follow
along with what we're doing here even if
you have no experience so the first
thing that we're going to want to
actually do is read this simple storage
solidity file we need to get this into
this deploy script so that our python
file knows what it's going to deploy so
how do we do this well we're going to
type with
open
quote dot slash
simple storage dot sol
comma r
as file
simple
storage file equals file dot read now
what is this actually doing
well it's saying that we're going to
execute some code
inside this indented area
after the colon and then once this code
is finished we're actually going to
close this file because right now we're
opening it we're going to close it once
it's done
the file that we're going to open is
going to be this simple storage.sol
which is located right here in this same
directory that we're in we're going to
only read from it and we're going to
call it file and then we're going to
read all the contents of this file and
place it in a variable simple storage
file
so then we can go ahead and write a
print statement print simple storage
file and if you hit save here you'll see
that it automatically gets formatted
which is really nice if you want to run
black yourself you can just type black
dot and it'll automatically format all
the python files in your folder here
you'll know that you're doing it right
if you add a whole bunch of new lines
and then save it anyways enough on
formatting let's head on down to the
terminal and let's call python deploy.pi
and we can see
our terminal printed everything in
simple storage file
which is perfect now our python script
has what it needs to actually get
started working with our solidity now
something you'll see i do a lot is i
save a lot and if you're looking for
some keyboard shortcuts you can always
do command p add a little bracket here
and look
up keyboard shortcuts reference
and click this
it'll bring you to this keyboard's
reference page based off of what
operating system that you have all right
great so now that we can actually read
from our simple storage.soul file we
actually have to compile it because
remember back in remix every single time
we did anything with our files we had to
compile them first
so we need some compiler in python
luckily there is a fantastic python
package called pi silk x that does
exactly this now i also want to point
out though that pi silk x is actually a
fork of this package called pi silk now
you can still use pysol however i'm
going to highly highly recommend that
you use pi silk x instead as pike sulk x
is a lot more actively maintained than
ethereum pixel we can install it with
pip install pi sulk x we could even hit
this little copy button move back on
over here paste it in and hit enter
again i've already installed it so it's
pretty quick for me the way that we can
use it now is by importing it into our
python here so we'll say from
sulk x
import
compile
standard compile standard is going to be
this main function that we actually use
to compile this code so let's go ahead
and compile
our solidity
we're going to save our compiled code to
a variable called
compiled soul
this is going to be equal to
us calling this compile standard
function
but we're going to add a lot of
variables and a lot of parameters into
this function here first we have to add
is a language
which in this case is
solidity we're going to add in some
sources
which we're going to say our sources are
going to be simple
storage.soul
and it's going to have some
content which is equal to this simple
storage file variable that we made
oh excuse me this all has to be in a
bracket piece as well
and see if i hit save here it auto
formats which is really nice and another
quick tip you can see how even my
brackets are highlighted in these fun
colors if we go down to extensions and
look up
bracket
you can add this bracket pair colorizer
which will help make the brackets look a
little bit nicer kind of as you see here
you can go ahead and install that as
well anyways then we'll add some
settings
and a lot of this is a little bit lower
level stuff than what you're really
going to have to know or use so i'm not
going to go too deep into everything
that's actually going on here for now
but in our settings
we're going to choose an output
selection
which is going to choose what we output
when we compile this
we do a little star here
and in the star we're going to do
another star
we're going to choose our output list
we're going to get an abi out that's
incredibly important which we've talked
about before
we're going to get some metadata
we're gonna get an evm dot byte code
we're gonna get an evm dot
source map
that's pretty much it again i'm not
gonna go too deep into what this output
selection and what these settings are
actually doing but if you want to learn
more you can go to the home page of pi
sulk x
scroll down to the documentation section
and read more in the docs on what you
can actually put and all the different
features that this actually has the last
thing we're going to do is we're going
to add a sulk version or solidity
version we're going to say
sulk
version
equals and then we'll choose the version
that we want to use so we'll put in
0.6.0
and then what we should be able to do is
print out
this compiled soul
and we'll see just a whole bunch of
really really low level stuff
so let's go ahead and run this we'll run
python
deploy.pi
and you'll see we get this
massive object here which has a whole
bunch of basically unreadable pieces but
this is a lot of the low-level code that
actually gets compiled whenever we use
the compiler in remix or now in python
remix actually does the exact same thing
once we compile something on remix you
can actually copy the bytecode if you
hit this little
copy button and copy the bytecode and
come back to your vs code and create a
new file a keyboard shortcut to create a
new file is command n and we paste
everything
we can see there's a whole bunch of
stuff in here these op codes are the low
level code that our contract is actually
doing that actually governs how this
code works this is what our written code
is getting compiled down to so solidity
can actually read it and understand
what's going on you'll also see this
thing called abi which is in remix and
we're even going to output it right here
we have this abi thing now in remix if
you hit copy the button on the api
come back
create new file paste it you can see we
have this long json object this is that
application binary interface that we've
talked about so much you can see that
it's actually describing all the
functions and variables
so for example
we have a function
called add person
and it takes two parameters a name
and a favorite number
so we have this input section for the
function and we have this section that
describes what the function can is
actually doing so the name is ad person
it doesn't have a return type it's
non-payable and it's a function and we
can see that for pretty much everything
in here this is the lowest digestible
way to say hey here's where all the
functions are here's what the parameter
types are here's what the return types
are going to be and everything like that
so we're going to close it out for now
though so this is fantastic we've now
compiled our solidity typically i
usually also like to output it and print
it out to a file as well so to do that
we'll do with
open
compiledcode.json
and this time instead of reading we're
going to write
and we'll call this as file as well
instead of doing file.write we're going
to do what's called a json.dump
compiled soul file
we do need of course to import
json also just a note i know it says
we're using sulk here but please use
sulk x still i ended up filming a little
bit of both versions so i did a little
bit of a mix and match but please use
sulk x even if you see seoul what this
line is going to do
is it's going to take our compiled soul
jason variable and just dump it into
this file here
but it's going to keep it in the json
syntax so it's still going to be json e
so now if we run python deploy.pi we'll
see we have a new file in here called
compilecode.json
the other reason that i wanted to do
this was because
if i hit control s
it actually formats this into a readable
way now again we can go into these
settings here
we can look up
json and we can do enable json formatter
and this will automatically make it so
that we format this json so it's a lot
more readable again the reason i like to
output this is because this abi is so
important and we're going to use it so
much that i like to kind of be able to
see it and and read through it really
quickly the rest of this lower level
stuff like evm and byte codes and op
codes we don't really work with so much
however as you learn more and more about
solidity you'll probably see more and
more of opcode so if you really want to
learn a lot of really low-level stuff
look into opcodes but for the purpose of
this tutorial we're not going to be
going too deep into it okay awesome so
we've compiled our solidity we've even
stored our solidity code to this
compiledcode.json file
now what do we do we probably want to
deploy it and test it out
so how do we actually do that well first
we actually have to get the bytecode we
need the bytecode of the file so that we
can actually deploy it so we're going to
do
bytecode
equals
compiled soul
contracts
simple storage dot sol
simple storage
evm
white code
object
all right great there we go so now we
have our byte code we also need to get
our abi so we need to get the api so
what we're doing here when we're typing
in all these words like contract simple
storage simple storage
is we're walking down the json here so
when we say we want to get the byte code
in this compiled solidity json we want
to go to contracts
simple storage symbol storage evm byte
code
so contracts inside this contracts json
you got to go to simple storage inside
this simple storage dot soul there's
another simple storage
inside that there's an avi but that's
not what we want we want the evm so
we're going to scroll down
we're going to get the evm then what do
we want then we want the bytecode great
and then we want the object so this
is the bytecode of our contract
it's the really low level stuff that
the ethereum virtual machine or the evm
is going to understand now we also need
the avi when we deploy this to a chain
this is what we're going to need we need
the byte code and the abi the abi we can
of course get from this kind of same
method here so to get this we can do abi
equals
compiled soul
same thing
contracts
simple storage dot soul
simple storage
and as you can see
we're right here and then we can just
grab this api object
avi
and we can even do print api we'll do
python develop.pi
and indeed our abi is printed here
awesome so now that we have our two main
pieces to deploy this now all we have to
do is deploy it but the question then
becomes is where are we going to deploy
it to which blockchain are we going to
deploy to in remix
when we were first playing around
we were using a javascript vm
or a fake or a simulated environment we
absolutely could and we absolutely will
learn to deploy this to a test in
because that's going to be the same way
that we're going to deploy to a mainnet
but before we do that we should learn
how to deploy this on a simulated
environment or something similar to that
javascript vm so it's much faster and
easier to test things and this is where
ganache is going to come to the rescue
ganache is a simulated or a fake
blockchain that we can actually use to
deploy our smart contracts to and have
it interact like it's a real blockchain
ganache is going to allow us to spin up
our own local blockchain
and it'll look something like this now
the user interface is really nice
because it allows us to kind of do this
one-click blockchain to create our own
local blockchain
that means that this blockchain isn't
connected to any other blockchain out
there but it'll act like a blockchain
but it'll be a lot faster than us having
to interact with a testnet and we
control the entire blockchain because
it's only one node we're the only node
so ganache great way to test things
quickly now we're going to mainly we're
working with the user
but i'm also going to show you how to
work with the ganache command line you
can really use either one depending on
what you want to do but a lot of the
tools actually have built-in ganache
command lines so it's definitely really
useful to learn that as well so again
ganache is going to be our simulated
environment here so what we're going to
do
once we get into ganache we can just go
ahead and hit quick start this will
automatically upload and get started
with our own local fake blockchain you
can even see it gives us some accounts
this should look pretty familiar it
should look very meta-masky right we
have an address here
and each one of these addresses has a
private key in your ganache you can go
ahead and just click the key and hit
show keys and it'll show you the account
address and the private key but of
course these are for development
purposes only each one of these accounts
has a balance associated with it we can
see a mnemonic or your secret phrase you
can see blocks transactions and a whole
lot of other really useful features here
and it even tells us
how to connect to this blockchain
and these are the connecting features
that we're going to want to use let's
learn how to connect to this ganache
blockchain from this user interface
first and then we'll learn how to do the
command line version this is when we
finally start working with web3.pi you
can just do pip
install
web3
and now we can start working with
web3.pi right at the top a little
confusingly
we're going to do import
web3
from
web3 whoops and this should be
from web3 import web3 sorry about that
now to connect to this blockchain we
choose what's called an http provider if
we look at this ganache instance we have
this rpc server which has this url http
0.0.0
this is the url that we're going to use
to connect to this blockchain in remix
we're actually using our metamasks
directly to connect to the blockchain
however we want to connect directly to
our simulated our fake blockchain right
here so what we're going to do is we're
going to do
w3
for
connecting to ganache
w3 equals
web3 web3.http
provider
of http
0.0.0.0
and it was on port
845.
port 845. now with everything that we
show you you're probably going to want
to get really familiar with the
documentation because even after being a
pro you're going to want to use it more
and more if you want to learn more about
other providers you can go to the
providers page of the documentation the
next thing that we're always going to
need as well is we're going to need the
chain id or the network id what is the
id of this blockchain
and for ganache it's one three three
seven
supposed to be a funny leat reference so
we'll do chain id
equals
one three three seven
now
we're also going to need an address
and address to deploy from
we can go ahead and grab one of these
fake addresses in here to work with
similar to how in remix when we were
working with the javascript vm we were
given a bunch of fake addresses we're
doing the same thing but with ganache
and then we're also of course going to
want a private key
we need the private key of course to
sign our transactions
so we'll do private key equals
this
now just note whenever you import a
private key in python you need to add an
ox to the front python is always going
to look for the hexadecimal version of
the private key awesome now we have all
the parameters that we need for
interacting with and connecting to our
ganache local chain it's time to finally
deploy our simple storage.soul contract
let's do it so the credit contract that
we're going to deploy with web3.pi we're
going to do simple storage
we're going to call this variable
w3
dot f
dot contract
and we're going to give it abi equals
abi
and byte code equals byte code great
does this mean we've deployed it well no
this just means we have a contract down
so we can do print simple storage and
you'll see if we run python
deploy.pi
we'll see we have a new type here
class web3.utils.datatype.contract
this is another type that if you want to
learn more you should definitely check
out the web3.pi documentation so we have
a contract object
awesome how do we actually deploy this
well we need to actually build our
transaction
because again whenever we interact with
the blockchain whenever we make a state
change and in this case we'd be
deploying a contract we're going to make
a state change so we first need to build
a transaction sign a transaction
and then send a transaction and to do
that we need to talk about that nuns
thing again remember way back in our
blockchain demo when we used a nuns to
solve the answer to that really
difficult mining problem well the
definition of nuns is just a word coined
or used for just one occasion and in
cryptography it's an arbitrary number
that can be used just once in a
cryptographic communication so this nuns
that's used to find the answer is going
to be different from another nuns that
we're actually going to need to make our
transaction see if we look at our meta
mask and we look at our activity
and we look at one of the transactions
we've made recently on etherscan
if we scroll down we'll see nuns
here as well this nunce is the number of
transactions that our account has
actually made every time we make another
transaction our transaction is hashed
with a new nuns this is what's going on
behind the scenes with our transaction
and we need this to send our transaction
we can actually get our nuns by just
grabbing our latest transaction count
get
the latest
transaction we can do
nonce equals w3
dot eth dot
get transaction count and we'll put in
my address
this will give us the number of
transactions and it'll effectively give
us our nuns
we can even test it out with a print
python
deploy
we can see we can see that the answer is
zero because on our local blockchain
this address that we're using hasn't
been used before we can even go to the
transactions tab we can see that there
are no transactions that have ever
occurred on our local blockchain now to
deploy this contract we need to make a
transaction remember everything that we
do every time we change the state of a
blockchain we're going to do it in a
transaction let's create a transaction
object to do this we can do
transaction
equals
symbol storage which again is this
contract object
dot
constructor
dot build transaction
now as you might have pointed out our
simple storage.sol doesn't actually have
a constructor every contract technically
has a constructor this one's is just
blank we're not telling our simple
storage.soul to do anything
we saw back in our fund me
example that the fund me example does
have a constructor so now we want to put
in some parameters for the transaction
in web3.pi we always have to give at
least a couple of parameters
we always have to give the chain id
which we already got from above which is
one three three seven
so we can just do chain id
we need a from
address in this case
my address
and then
we need a nuns
which in our case is just nuts
great now we have a transaction object
let's even print this out and see what
it looks like
whoa what's this we can see there's even
more parameters in here than just what
we made
so we have value which is the ether or
the ethereum that we're going to send we
have gas we have our gas price which we
could arbitrarily set if we'd like
we have the chain id we have from
address we have the nuns
and then we have this giant data object
and then two is just empty because it's
sending it to the blockchain this giant
data object here is encompassing
everything that's happening in this
simple storage dot sol now that's just a
transaction and anybody could actually
send this transaction as long as it's
signed by them so we have this
transaction but we need to sign it from
somebody since we're sending it from our
address
our private key is going to be the only
key that's going to work to sign this
remember back when we were talking about
public and private keys we right now
have a message that is defining how to
deploy simple storage but it's not
signed yet so we're going to need to use
our private key to sign it to create
this unique message signature that we're
the only ones that can create the
private key but anybody else can verify
that it was us who signed it so now
signed
transaction
equals web3
dot eth
dot account
dot sign transaction
and the parameters it takes are going to
be transaction
and then private key
we're gonna say the private key equals
private key because above we've actually
gone ahead and added our private key in
here now guys a really really important
note about putting a private key in your
code this is really bad practice if you
push this to source or you push this to
github somebody else can see your
private key and steal all your funds so
we don't want to hard code our private
keys in our code like we're doing here
so let's take this time to talk about
environment variables and how to set
them environment variables are variables
that you can set and that we set in our
terminal and in our command lines the
following is a way to set an environment
variable in macos and linux only don't
worry we'll show a way to make an
environment variable in windows as well
you can set an environment variable by
running something like export
private key
equals
and then adding whatever variable that
you want
now if you type echo
dollar sign private key
this variable actually shows up to set
environment variables with windows the
process that we're going to do is
actually a little bit different
i've left a link in our github to
actually set environment variables in a
windows setting
and we've left a couple of really
helpful links for working more with
environment variables you should
definitely check them out it's important
to note that this export method that
we're doing here for creating
environment variables only works for the
duration that our shell is live so if we
were to close out of our shell and then
reopen it our environment variable that
we set would be gone so we'd have to
re-run that export command we're gonna
show you a way to set environment
variables so that you don't have to keep
doing that now it's also not great to
have in plain text on your computer
however it's a lot better than hard
coding it into our script here now
remember if you're using an account that
has real money in it which i highly
recommend you do not do don't send this
environment variable or this private key
or any of this code anywhere because
then people can steal all your funds
once we move to brownie we'll show you a
more effective way for private key
management but for now be cautious here
but if you followed along and set up a
brand new account that has no real money
and only test that money in it then
great who cares because it's test and
it's fake money anyways
i think i've talked about it enough
anyways let's get back to it we can
actually access this environment
variable in python using os.get env
we just need to import os
and now we can access our private key in
our script without actually hard coding
it in
let's see what happens if we do print
private key python deploy to pi
you can see our python script was able
to pull our private key from our
environment variable the other thing
that we can do is create a dot env file
a dot emv file is typically where people
store environment variables it's
important to not push these to source if
this is what you're going to do in this
dot envy file in python we can just do
export
private key and then same as what we did
before
add the 0x at the start and then private
key so we could put 100 environment
variables in here
export
some
other var equals
seven
if you're going to do it in this way
please please please
always set a dot git ignore
and make sure dot env is in here this
will help make it harder for you to
accidentally push your env folder or
your emp file to github python actually
has a way of loading directly from a env
file without having to export our
environment variables or run source.env
or export or really anything and we can
do it with this python.env package
if we close our shell and then reopen it
if we run echo
some other var
we're going to get none here and in fact
if we run
python develop.pi when we print this
environment variable we're going to get
none
however we can use this.env to have it
pulled directly from our.emv so we just
do pip
install
python.env
i've already downloaded it so it just
says requirement already satisfied and
then
what we can do at the top of this we can
do from
dot env
import
load.enb and we can run
a load.enb function right at the top
this load.env looks for this.env file
and automatically imports it into our
script so if we run this now you'll see
that the environment variable was
successfully imported into our script
and now we can use it so let's let's use
it for example with our private key
private key
equals os that get
private key now we can even print it out
just a test
we'll run our script
and awesome
we can see our private key is being
successfully pulled in and we didn't
hard code it into our application
all right let's get back down to our
signed transaction here now let's go
ahead and print this out and take a look
at what this looks like now we can run a
script and great what we see here is an
example of a signed transaction remember
this is exactly what's happening when we
were looking back at public private keys
we are signing a transaction that is
actually deploying a contract to the
blockchain that anybody can easily
verify all right so we finally have our
signed transaction now we want to send
this to the blockchain so it actually
can deploy let's send
the signed transaction
we can do transaction hash
equals
web3.eth
here's a little helpful tip if you see
this little box underneath with
suggestions show up and you just hit tab
it'll auto complete the rest of your
text here that's send raw transaction
and we'll give it
our sign transaction
dot
broad transaction this will send our
transaction to the blockchain now if we
look at our local ganache and we look at
transactions right now it'll be empty
but let's see what happens when we run
this script
okay so we didn't print anything out but
if we go to our ganache we can see that
a transaction actually did go through
it was from the address that we put in
here we created a contract at this
address
this is how much gas it used
and this is how much value was sent with
it we can even click on it to see more
information about this now this is the
other advantage of doing this locally is
that the transaction automatically went
through we've sent our first transaction
to a local blockchain and this
transaction is deploying a contract
great work you can already see how much
faster this is than working with a test
net one other thing that's really good
practice whenever sending a transaction
is we wait for some block confirmations
to happen
so we can do
transaction
receipt
equals web3 dot eth
wait
for transaction receipt
txhash
this will have our code stop and wait
for this transaction hash to go through
awesome so i just ran it again and if we
go to transactions
we can now see that there are two
transactions here
and our code waited a little bit longer
for this one to complete so of course
we've deployed a contract but how do we
actually interact and work with the
contract let's start doing that so when
working with contracts and we're working
with on chain whenever we work with a
contract we always need two things
we need the contract address and the
contract abi often times if you're
looking for a specific abi of a type of
contract you can usually just google it
so we need to make a new contract object
to work with contracts let's go ahead
and create this simple storage contract
so we can actually interact with it
so we'll do simple storage
equals
dot w3.eth.com now we need our address
which we can get from ganache
but that might be a little bit hard to
always be checking the blockchain for a
transaction
it's actually also in this transaction
receipt address
equals transaction receipt dot contract
address
and then since we've compiled this we
also have our abi already
abi
equals abi
sometimes you'll see people have a file
called
abis.pi or abis.json or something like
that and they'll load apis in directly
from there and great now that we have
the address and the api we can start
interacting with this contract exactly
as we did in remix so let's do a print
statement to get that initial value that
is returned from our retrieve function
remember it should be initialized to
zero
so if we do print
simple storage dot functions
dot retrieve
let's see what happens here
huh what's this
we get this function retrieve bound to
in these parentheses here
so what's going on when making
transactions in the blockchain there's
actually two different ways that we can
interact with them we can interact with
a call
or we can interact with a transact when
we use a call
this is just to simulate
making the call
and getting a return value
calls don't make a state change to the
blockchain and it's similar to how in
remix we would call these blue buttons
and nothing on the blockchain would
actually change we can actually also
call these orange buttons or these
non-view functions and just not actually
make a state change remix defaults these
blue buttons to be calls and these
orange buttons to be transacts in python
we can actually pick which one we want
to do a transact a transact call is when
we actually
make a state change
and this is when we actually have to
build a transaction and send a
transaction you can always just call a
function no matter what that function is
but just keep in mind you won't make a
state change you can also always
transact on a function even if it's just
a view and this will attempt to make a
state change
something like retrieve even if we
transact on it it won't make a state
change so for something like retrieve
where we don't actually want to make a
state change
we just use the call function so we'll
just do dot call
now
if we try to run this
you'll see we do get the zero because
now we're actually calling this
transaction awesome so now we have our
initial value for our retrieve function
let's keep going let's try to update
this favorite number using this store
function this we'll just keep in mind is
our initial
value of
favorite number we know that this store
function is orange and we'll actually
make a transaction
but if we wanted to we can even just use
call on it
we'll do simple storage
dot functions
that's store
we'll put that 15 in here
call
let's see what happens when we send this
you can see it returned a blank that's
because this store
function has no return type if we give
this returns
unit 256
and then we say return
favorite number
and now we go back here
and we run this again
you'll see now that we get a 15 back if
we go to ganache you'll see that we keep
making a whole bunch of different
contracts but none of these are contract
interactions that's because when we call
a function we just simulate working with
it if we call retrieve again right
afterwards you'll see that it's still
zero
it's because calling is just a
simulation now let's delete all that so
let's actually build a new transaction
to actually store some value
into this contract since we want to make
a transaction we got to go through the
same process as when we deployed this
contract
let's first create a transaction
called store transaction
equals
simple storage
dot
functions
about store
and we'll give it some number in this
case 15
and then we have to do dot
build transaction
and we'll put those same pieces in here
from before we're going to have
chain id
be the chain id
we're going to need from
give me my address
nunce
is going to be the nuns
plus 1.
we're going to need to do nuns plus 1
because we actually use this nuns
already
when we create our initial transaction
remember a nuns can only be used once
for each transaction
so this transaction is going to have to
have a different nuance than the nuns we
use to deploy the contract now that we
have the transaction let's go ahead and
sign it
we'll do signed
store
tx
and
we'll do web3
that eath
dot account
dot sign transaction
store transaction
and then private key equals
private key and we'll go ahead and save
then of course we need to send it so
we'll do
transaction hash
equals w3.eth
dot send raw transaction
signed
store transaction
dot raw
transaction
and let's grab that transaction receipt
again
by doing transaction receipt
equals w3
dot eth
dot wait for transaction receipt and
actually let's call this
send
store
tx
that way for receipt
send store tx awesome it looks like
we're following the same steps here as
we did above
we created the transaction
we signed the transaction
and then we send the transaction
down here
we create a transaction
we sign the transaction we sent the
transaction and then we waited for the
transaction to finish
so let's run this
all right great we still have this print
function printing out the current value
of retrieve let's go over to ganache and
see if there's anything different here
there is instead of all these contract
creations here we now have a contract
call
we can see there's some transaction data
that was sent
a different amount of gas same gas
prices
however
this
actually updated and sent the
transaction to our blockchain
now if we call this retrieve function
again
this should print out our newly updated
value which in this case was 15.
let's go ahead and run
python deployed up high
and we can see it started at zero
and then it turned to 15. awesome we've
made our first state change to a
contract that we've deployed on our
local blockchain great work sometimes
it's nice to put some lines in here to
tell you what's going on to make it a
little bit more clear so i'll put
something like
deploying
contract dot dot
right before we deploy our contract
after we do it i might do
deployed
then
right before we update our contract
we'll print out something
like updating contract
and then right after it's done
maybe something like
updated
now if we run this now
you'll see as this goes along we'll get
these things printed out saying
deploying contract contract deployed
updating contract updated this will make
those moments when waiting for these
contracts to actually finish a lot
easier you're doing fantastic so ganache
user interface is really nice because we
can see a lot of things that are going
on here however it's a little tricky to
do a lot of programmatic stuff
oftentimes engineer will use what's
called a command line interface of
ganache instead of the ui so we're going
to go ahead and close this out and we're
going to use the ganache cli instead of
that user interface that we just saw and
this is what and this is what brown is
going to use on the back end when we
move to brownie let's learn how to
actually do that so in order to use the
ganache cli or command line interface
the first thing that we need to do is
download node.js yes i know this is a
python video however we do need to
install node.js to work with the ganache
cli you can come to this download page
and choose your operating system and
download it accordingly we will link to
a video showing you how to do this in
the github you'll know you've done it
right if you can run node
dash version in your command line and
you get a version it might be 12 might
be 14 might be something else depending
on what version you downloaded next
we're actually going to install yarn
yarn is a package manager similar to pip
and will allow us to actually download
pieces and packages like the ganache cli
from the package repository we can
install it with npm install dash dash
global yarn and you'll know you've done
it right
if you can run yarn
dash dash version in your command line
and you get the version outputted here
then we want to install the actual
ganache cli we're gonna be installing it
with yarn so to install this we're gonna
yarn global
add
ganache cli
this will install our ganache cli as a
global command in our terminal we can
test to see if we've done it right if we
can run
ganache
cli
dash dash version perfect we now have
the ganache cli let's spin up a ganache
chain with the cli
if you have your ganache ui open right
now please close it otherwise it'll
conflict so to run a local blockchain
from the command line all you need to do
is run
ganache
cli
and the node will start running directly
in your terminal
if you scroll up you can see a lot of
familiar pieces
we see the available accounts just like
on the ui
these are the different addresses
and then we see a whole bunch of
different private keys this ganache
spins up with a bunch of random
addresses and random private keys if we
wanted to always spin up with the exact
same private keys so we don't have to
update our private key every time
we can do ganache
cli
dash dash
deterministic
this way we'll always get the exact same
private keys
and the exact same addresses you can
check out the documentation to see a
bunch of other flags that you can use to
run this and you can see it's listening
on 127.2
127.0.0.1 is also known as the loopback
address or localhost now to work with
ganache in the command line
all we need to do now is update our
private keys and our addresses let's
also update the http provider since now
we're going to be looking at the
loopback address for my address
we'll scroll up
to this top address here
and we'll place it in
for our private key
we're going to copy this
and put it into our dot emv file
it already has the ox at the top here
great now let's open up a new terminal
you can open up a new terminal by
hitting this plus button here
and you can flip back and forth by
hitting this drop down and flipping back
to the ganache terminal now let's go
ahead and run
python
deploy.pi
we can see
the exact same output as we got when
working with the ui and if we flip over
to the command line we can see we've
made a whole bunch of different calls to
our blockchain each one of these calls
is a specific json rpc call to our
blockchain that we're making to interact
with it we can see information about the
transactions that we send this one
creates our simple storage contract
this one updates our simple storage
contract and great you now know how to
work with the ganache cli and the
ganache ui fantastic so how do we
actually deploy this to a test net or a
real network we were working with remix
all we had to do was switch to injected
web 3 and we used our meta mask as our
blockchain connection well in our script
here we don't have metamask natively
with our script so we need some way to
connect to the blockchain we can see
that when we're connecting to our own
local blockchain we just use an rpc url
that connects to our local blockchain to
connect to a test net or to a mainnet we
can actually do the exact same thing all
we have to do is swap this out with the
url that connects us to a mainnet or a
test app we can also run our own
blockchain node similar to how we're
running our own local blockchain node we
can run a node that actually connects to
a real blockchain however it's not
always practical or really easy to do
this so sometimes we want to use an
external or a third-party client that
actually will run a blockchain for us
let's learn a little about inferior
inferior.io is an application that will
give you a blockchain url for you to
connect with for you to run whatever you
want to run and you can get started for
free let's go ahead and register
then we just check our email
confirm email address and awesome now
we're inside of infira there's a couple
other services out there that you can
also check out like alchemy which is
another fantastic blockchain as a
service platform fura is a freemium
service it starts out as free if you
make too many api calls or too many
calls to the url they'll start charging
you
but we can create a project for free for
now let's go ahead
hit the ethereum tab
hit create project we'll call
this free code camp
brownie
hit create now we'll have a whole bunch
of project keys and project secrets we
also have this endpoint section as well
this is how we're going to be deploying
to the different networks we can see we
have an ethereum mainnet connection as
well as robson coven rink b and gorilla
testnets there's also polygon in here as
well since we want to test and deploy to
a ring b chain we can go ahead and move
to ring b and then
we can copy this url back in our
application all we have to do is swap
this out
for the new url we also have to change
the chain id
our address and the private key if you
ever are confused as to what is the
chain id of the chain that you're
working on you can always check this
chain id dot network or you can usually
ask somebody let's look up ring b we see
the chain id is four so we'll grab four
and we'll place that in our script now
this address and the private key that we
gave it now this address and the private
key that we gave it aren't going to have
any testnet ring be in them so we need
to go in our metamask and grab the
address place it in for address and then
account details
export private key
type in our password
and grab the private key go into our dot
emb file
leave the 0x and replace the rest with
our private key since i have my private
key stored as an environment variable i
need to then run source.env so that my
private key is now updated the reason
we're using this is because again since
we're making transactions to a testnet
we need some test and eth alright so now
we have everything updated for deploying
to rinkeby let's go ahead and run this
now
as you can see it's going a lot slower
this is because we actually have to wait
for the contracts to get mined and for
everything to happen
on the test net deploying to a tesla
will result in nearly the exact same
experience that you'll get when
deploying to an actual main net so it'll
take a lot longer but you can see we got
the exact same responses here now if we
take this address
and we go to the rink be ether scan
we can verify what just happened
we can see that 38 seconds ago
we made this transaction
and then 23 seconds ago we made this
transaction
we can look at all the different details
of this transaction that we just made
from our python script
we can see it even tells us we created a
smart contract
and then
we made this call
which called this store function on this
contract
we've learned a lot so far this is
fantastic now is a perfect time to take
a break and take a quick breather and
reflect back on what we've just learned
we've learned a lot about python
deploying to our own local blockchain
deploying to a test net and deploying to
a mainnet working more with private keys
creating transactions
signing transactions and then sending
transactions
now as you can see there's going to be a
lot to actually managing all the
contracts that we work with having to
write our own compile code our own
storage code is going to take a lot of
work and what if we wanted to interact
with one of the contracts that we
deployed in the past well we'd have to
keep track of all those addresses and
manually update our address features
here with an address maybe we didn't
want to deploy a new contract every
single time maybe we want to work with a
contract that we've already deployed
what if we want to work with a whole
bunch of different chains what if we
want to work with rink b and mainnet and
our own local network there seems to be
a lot to manage here and we still
haven't even talked about writing tests
this is where brownie is going to come
into play brownie is currently the most
popular smart contract development
platform built based on python it's used
by d5 giants like yearn.finance
curve.phi and out each having billions
of dollars currently locked in value and
the reason that we learned a little bit
about web3.pi first is because brownie
heavily relies on web3.pi so let's do
all this again but in brownie and we'll
see how much easier it is to actually
interact with in our shell
let's go back one directory and let's
make a new one we'll call it
brownie
simple
storage
now another really cool trick that vs
code has is instead of us having to go
to file and open up this folder in this
explorer here
what we can do is we can type code
and then type the directory that we want
to work with in our case
this directory so we can just type code
dot
and we'll get a new vs code pop-up
inside of this brownie simple storage
folder let's get learning about brownie
and this is where you're going to spend
the majority of your time move forward
brownie is incredibly powerful and makes
our lives fantastically easier so get
ready to learn one of the most powerful
tools in the smart contract developing
ecosystem let's go ahead and open up our
terminal and let's get started
installing brownie it's recommended to
install brownie via pipex pepex installs
brownie into a virtual environment and
makes it available directly from the
command line once installed you'll never
have to activate a virtual environment
prior to using browning which is really
good to install it with pipex we can go
ahead and run python dash m
pip install dash dash user pipex
once we've run that we can then run
python3-m pick at pipex in surepath
then we'll want to close the terminal by
hitting the little trashcan and then
reopen it and then we just need to run
pipex install f brownie i've already got
it installed so that's why we see this
here and then just one more time we're
going to close and reopen the terminal
you can tell you have brownie installed
correctly if you run brownie dash dash
version
and you get some output that looks
something like this
or you just run straight up brownie
and it'll output a bunch of commands
that we can run let's create our first
brownie project
we're going to be using the exact same
simple storage code that we just went
through except for we're going to use it
in brownie this is going to make our
lives a lot easier when working with
simple storage to create a sample folder
with everything we need with brownie we
can just run brownie
init
and we will get a new brownie project
initialized in the directory that we're
currently in
if you type ls you'll be able to see all
the folders that are created or you can
just see them on your side panel in vs
code let's talk really quickly about
what each of these folders is going to
do the build folder tracks a lot of
really important low-level information
it's going to track any interfaces that
we're working with or deploying it's
going to keep track of all of our
deployments across all of the different
chains so we no longer have to manage
that ourselves
and it's going to store all the compiled
code remember how in our simple storage
code we actually saved everything to
this compile code.json well brownie is
actually going to do all of that for us
into this contracts directory so we can
always reference it later this contracts
directory outside the build folder is
where we're going to put all of our
contracts brownie knows to look inside
of this folder when looking for new
contracts to compile deploy or anything
else interfaces is where we can save and
store different interfaces remember how
when we were working with chain link
working with interfaces makes it really
easy to interact with a blockchain
application reports are to save any type
of report you run scripts or we can
automate tasks like deploying calling
different functions or really anything
we want and then we have a test folder
which is incredibly powerful and we're
going to be using a lot we also have git
attributes and get ignore which are
helpful when working with version
control like git so let's go ahead and
start working with brownie and really
understand what's going on here so let's
go ahead and add our simple storage
contracts to the contracts folder so in
here we're just going to make a new file
we'll call it simple
storage.soul and i'm just going to copy
and paste the code i have
from the simple storage that we've been
using this whole time let's go ahead and
save that with command s okay great now
that we have our contract in here we can
already start working with brownie and
even compile this code without even
having to write or work with our own
compiler all we need to do
is run brownie
compile
brownie will automatically read the
version of solidity and then store all
of the compile information in this build
folder so if we go to contracts we can
see we have a simple storage.json and
there's a lot of familiar pieces in here
for example we see the abi opcodes
section which is the low level language
we'll see a pc map and we'll see a lot
of useful information and great
obviously deployments and interfaces are
still empty so great we've already
compiled our smart contract so why don't
we actually deploy this to a blockchain
to do this we do have to write a script
which will allow us to do whatever we
want so we're going to create a new file
and we're just going to call this
similar to last time deploy dot pi this
is where we're going to define working
with and deploying our code brownie can
run scripts by running brownie run in
fact if you want to take a quick minute
to familiarize yourself with all the
different commands that brownie has just
run brownie and you'll see we can do a
lot of different things we do brownie
init which will create a new brownie
project we will do brownie bake which
allows us to pull from the brownie mix
which we'll talk about later we can
compile we can go into a console test
run we do a lot of wonderful things in
here if we do brownie run it'll run a
script for us and we can define that we
want to run this deploy all we have to
do is add a def
main
so def in python is the way to define a
function we're going to call this
function main and for now let's just say
print
hello
and we can run
brownie
run
scripts deploy
and as you can see it automatically does
this launching thing
so brownie defaults to always working
with a local ganache cli blockchain it's
running the exact same command that we
ran earlier and it has a bunch of
different flags like accounts 10 a
certain hard fork a certain gas limit
etc so at the beginning of all of our
scripts if we don't give brownie a
network to use it'll spin up a local
ganache and at the end of the script
it'll tear it back down typically what i
like to do is actually put all the logic
of our deployment in its own function
def
deploy
simple storage
and we'll do pass for now and then our
main function we can just call
deploy symbol storage now in order to
deploy our contract let's look back at
our web 3 pi version of deploying this
and see what we did so first we compiled
it great brownie does that automatically
then we jumped into a file great brian
does that automatically
we got a byte code and an abi
great brand does that automatically we
added a local blockchain to use great
brownie automatically spins up a local
ganache we'll learn how to do test nets
in a little bit aha we do need an
address though and a private key so how
do we actually get our private key get
our account into brownie brownie has an
account package that actually natively
understands how to work with accounts
and we can import it into our script
here so we can do from
brownie import accounts
and with this accounts keyword
we can add an account a number of
different ways if we're going to work
with our local chain as you see here the
ganache cli will spin up 10 fake
accounts for us and brownie
automatically knows that we can work
with that account so we can do something
like account equals account zero and
then just do something like print
account so we're going to take the
account that's spun up at the zerowith
index because this accounts object is
just an array so if we run this now
brownie
runs scripts
deploy
it's going to spin up us an address and
a private key that we can just work with
without having to define a private key
or do anything it does all of that for
us which is fantastic we do of course
still want to know how to add our own
private keys so that we can work with
the test net so this is great and works
when we're working with a development
network or working with brownie's
automatic ganache cli if we want to work
with a test net though we have to do
something else another way to add your
accounts in brownie is to use the
command line and actually add them
natively into brownie we can do brownie
accounts
new and we'll give it a name free code
camp account
this will then prompt us and say enter
the private key that you wish to add
let's go ahead and grab our private key
from metamask account details export
private key
put your password in
grab the private key and then we just
add ox and paste it in
brownie will actually password encrypt
your private key in this way
so we'll give it a password and now we
have a new account natively integrated
into brownie to see it we can do brownie
accounts list and you'll see that we
have a free code camp account with this
address and also a testing account i
made this a little bit earlier we can
get rid of it
by running brownie
accounts delete
testing helpful terminal tip time so if
you hit up or down on your keyboard you
can actually toggle through the history
of the commands that you've written so
if you hit up it'll actually bring you
to the most recently run command which
can allow you to run previous commands a
little bit faster and if we run browning
accounts list again
we'll see it's now just free code camp
if we want to work with this free
codecamp account that we've added to
brownie via the command line
we can get it with account
equals accounts dot load
free code camp account
and then we can do print account let's
run this script again
this time when we on the script it's
going to ask us for the password we need
to enter the password to decrypt the
account because right now it's password
encrypted so we're going to type in the
password and it's going to go ahead and
execute with our unlocked private key we
can see the address it printed out was
right here
and if we copy the address and we go
back we can see that that is correct
now if we're going to talk about safety
and you want to safely secure your keys
this is one of the safer ways to do it
because it's not going to store it in
git
you're not going to accidentally push it
up to github or show it to anybody and
it's going to be password encrypted this
is going to be one of the ways that i
highly recommend you store your keys
oftentimes you're going to want to do a
mix of working with the local ganache
ones and your own keys and we'll learn
how to flip back and forth between them
in a little bit now the third way that i
like to use is still again using an
environment variable script oftentimes
it's really easy just to have your
private key be an environment variable
this way you won't have to keep putting
the password in every single time you
run a script so it's a little bit less
secure and just another tip for myself i
never put my private keys associated
with wallets that have real money in
them as environment variables or in a
env file just in case i accidentally do
something really stupid i don't trust
myself enough so i'm gonna highly
recommend that whatever private key that
you use and you store it as an
environment variable here always have it
be just kind of a test account that
you're gonna use to test things and then
for some of your more serious accounts
that's what you'll use the encryption
for so let's go ahead and create an
environment variable file
so we'll do a new file call it env
and we'll do export
private key
ox this
now we have a private key set as an
environment barrel so brownie has an
additional feature that allows us to
easily work with environment variables
in an environment variable folder we can
tell brownie to always pull from our env
file in a brownie config
yaml
this is a special file that brownie
always looks for to grab information
about where you're going to build where
you're going to deploy and where you're
going to grab things in this config all
we need to do is add env
and set dot env this is telling brownie
hey when you run scripts grab the
environment variables from the dot env
file and what we can do is after we
import os we'll do account equals
accounts dot add os dot get env this is
how we get that environment variable a
private key then let's just print out
that account see if we did it right
brownie run
scripts deploy.pi
and great
all right great so this seems to work
perfectly but i like to make this method
even more explicit so we're going to
take this version that we just learned
and improve it in our brownie config we
can actually add more information about
what wallets we want to use and when we
want to use them
what we can do
is we can add a wallets section
and add in here a from
key section
and then add that environment variable
private key in your yaml file if you
surround a string with dollar sign and
some curly brackets it will
automatically get transformed into the
environment variable so if we go back to
deploy we can actually change this we
can grab right from our config file so
we'll do from brownie import accounts
config
instead of using os
we can do accounts
dot add
config
and then we'll do wallets
since that's what we're defining right
here
and then from key
wallets
from
key
and this will do the exact same thing as
our os dot get emv
the reason that this is better is
because now we have one canonical place
where we're always going to pull our
private key from instead of having to go
through all of our scripts and update it
based on whatever we change an
environment variable now let's try this
out
brownie run
scripts deploy
and great we see our address printed
here
for now let's just stick with using
accounts zero since we want to just use
the account that brownie makes for us
with ganache now brownie is really
intelligent and we can actually go ahead
and import
a contract directly into our script and
a web3.pi version we opened a contract
and read from it and that's how we were
able to interact with it after we
deployed it in brownie what we can do is
from brownie
import
and then just the name
of the contract simple storage then
we can do simple storage
dot deploy and this is how we're going
to deploy it to a chain anytime you
deploy to a chain or you make a
transaction you always need to do a from
and then say who you're going to be
deploying from what's the account that's
going to be deploying this as you can
see
this step of just deploying is
much quicker
than what we did in web3.pi in web3.pi
we had to
get the byte code and the abi then we
had to get the nuns
we had to create the contract we had to
create the transaction
sign the transaction and then send the
transaction remember how i said before
you could either make a transaction
or a call brownie is smart enough to
know whether or not what you're doing is
going to be a transaction or a call
in this case since we're deploying a
smart contract brownie's smart enough to
know that ah we want to make a state
change so let's make a state change
it'll return a contract object
so we can just add print
simple storage and we'll see what prints
so let's run this brownie run scripts
deploy.pi
awesome so what happened was brownie
again per usual it launched a local
ganache chain
and then it sent a transaction to deploy
simple storage
and it says simple storage deployed at
and then the address it was deployed at
and we can see how much quicker this is
to actually deploy now let's go ahead
and do exactly what we did with web3.pi
let's call this initial retrieve
function and then we'll update it with a
new value of 15. but we'll do it in
brownie now
remember here's how we did it back in
web3.pie in brownie what we're going to
do is first we're going to do
stored value
equals
simple storage
dot retrieve now since this is a view
function we don't have to add from
account in here again brownie is
intelligent enough to know if this is a
call or transaction and we know that
retrieve is
a view function so we know we don't
actually have to make a transaction here
then we can print out the value of
stored value
print
stored value
let's go ahead and try this
great we get 0 right here perfect
now let's try updating this so we can do
transaction
equals
simple storage
dot store
and in here we'd want to do 15. but
remember since we're doing a transaction
in brownie we always have to add who
we're going to transact from
in this case we're going to do from
account similar to web3.pi we can do
transaction.wait
for how many blocks we want to wait and
then let's call that retrieve function
again to see if it's been updated
so we can do updated
stored value equals
symbol storage dot retrieve and then we
can print
the updated stored value
and if we run this
we now see we have two transactions here
one that deployed our original simple
storage contract and we called the
retrieve function and we returned zero
here
then we updated with our store function
and then we called retrieve again and we
see we did indeed update it to 15. you
see how much smaller and easier and more
intuitive this is in brownie and how
much our lives are going to be much
better awesome now you've learned how to
deploy to a local chain now running
these scripts is fantastic but we need a
way to actually automate that our
contracts are doing what we want them to
do we don't want to always have to
manually check that all of our stuff is
doing what we want to do right we don't
want to have to manually check that 15
is actually updating appropriately this
is why running tests are so important
and automating your tests is going to be
crucial to becoming a successful smart
contract developer now i do want to
point out that you actually can write
tests directly in solidity and this is a
great way to actually test your smart
contracts is to learn how to do it right
in solidity however a lot of the
professional developers code their tests
in the smart contract development
framework language like python or
javascript doing it in this way allows
you to get a lot more flexibility and
customization with what you're doing
with your smart contracts and not being
confined to whatever only solidity has
so let's go ahead and learn how to
actually write our smart contract tests
in python this is what this test folder
is for so we're going to create a new
file called test
simple storage
dot pi
make sure you do add tests to the front
of these because this is the syntax that
pi test is going to be looking for and
then in our test we can actually set it
up the exact same way we set up our
deploy function we can do from
browning
import
simple storage
and accounts
then we can start defining our tests we
want to test to see that when we deploy
our smart contract that it gets started
off with zero in that retrieve function
so we'll create our first test we'll do
def
test
deploy and typically
testing in smart contracts or testing
really in anything is going to be
separated into three categories
arranging
acting
and asserting we're going to bounce
around and be a little bit loose with
this definition for the duration of our
tutorials here however keep in mind that
typically this is the setup that you
want to use later on in one of our later
smart contract examples we're going to
go through a much better testing setup
so in our arrange stage we're going to
set up all the pieces that we need to
get set up
so first
we're going to grab an account
we're going to say accounts equals
account zero and this is really all we
need to do to start getting set up now
for our acting stage we're going to
deploy
a simple storage contract
exactly as we did with deploy
so we do simple storage
equals simple storage dot deploy
from
account then we're going to get our
starting value
starting value
is going to be equal to
simple storage dot
retrieve and we're expecting
[Music]
this to be zero
so then all we have to do in our search
sage is we have to run assert
starting value
equals
expected so let's recap this in our
arrange stage we're just getting our
account so that we can actually make
contracts then in our x stage we're
going to deploy this simple storage
smart contract we're going to call the
retrieve function to see what its
starting value is and we're going to
compare to see if that starting value is
what we expect and we expect it to be
zero we can then test this with brownie
test
and per usual brownie is going to kick
off a ganache lie
and then it's going to test this
for every test you have you're going to
get a little green dot and we're going
to say one pass in 1.86 seconds which is
perfect if we had expected to be 15 and
we ran brownie test we should get a fail
here
awesome and that's exactly what we got
now let's go ahead and test updating
this with 15 and see if it works as we
want it to so we can do a new test in
here
we'll do def
test
update thing
storage
and we'll do those three phases
arrange
act
and assert in our range all we need to
do is get our account
from account zero and in this one
arranging is also going to be deploying
our smart contract
since this is really just part of the
setup and not the act that we're really
testing now in our act we're going to
add expected
to be equal to 15 and we're going to run
simple storage
dot store
expected
and then from account
you'll notice this is nearly exactly the
same as this deploy function here
now same as last time all we have to do
is assert
expected
equals equals
simple storage dot
retrieve we're saying we want to store
15 in our smart contract and then when
we call our retrieve function it is
stored correctly so let's go ahead and
run
brownie test
awesome we can see two dots here this
means two have actually passed correctly
that's great now i do want to quickly
show you a couple of useful tips that i
pretty much always do when i'm running
my tests if you want to test just one
function you can do dash k
brownie test k
test updating storage and we will only
test this test updating storage we can
run brownie test dash dash pdb
and add something wrong in here like
five equals simple storage dot retrieve
and what will happen is once this kicks
out and is wrong will actually get put
into a python shell and now we can check
to see some variables in here like if i
see what expected is expected is 15.
if i try to run
simple storage.retrieve expected is 15.
if i run simple storage
i'll see this is the simple storage
contract
pdb is a really useful way to mess
around and see okay well what did i
really go wrong why is my test failing
another important flag is going to be
dash s
so you'll notice that no print lines
actually get sent out when you're
working with these tests
if you do dash s
it'll be a little bit more robust and
telling you exactly what's going on and
if we had any print lines it would print
the lines out as well everything that
you can do with brownie test actually
comes directly from pi test so if
there's some flag you want to use or
some awesome debugger you want to use
you can use it with brownie just by
looking at the pi test documentation all
the tools are exactly the same all right
we're coming along fantastically we have
a script to deploy we have some tests we
have our contract this is great but now
we actually want to deploy to a test net
how are we going to do this let's look
at back how we did it with web3.pi back
in web3.pi to deploy this to a test net
we just needed to add our http web3
provider which was our infira account
and that was pretty much it and add our
address and our private key brownie our
lives are even easier brownie comes
pre-packaged with a list of networks
that it's already compatible with you
can see all the networks by running
brownie
networks
list
now mine has a couple more actually
because i've been playing around with
this for a long time but if you want to
see all the different networks you can
look at this list here something
important to note is that there's a
difference between the development
networks
and the ethereum networks whenever we
deploy to a network we default to this
development network any network that you
see under this development section is
going to be a network that is temporary
these are networks such as the temporary
ganache network that brownie
automatically spins up when we've run
any of the scripts we've written so far
so this is really important to know
remember anything in this development
section is going to get torn down
after it's deployed however the ethereum
ones are going to be our persistent
networks anything under this ethereum
tab brownie is actually going to keep
track of our deployments and keep track
of everything in there these networks
under here represent persistent networks
like mainnet rink b coven etc now in our
web3.pi we used an rpc url or an http
provider from infira to connect to a
testnet we're going to use that exact
same methodology here so how do we
actually get this rpc url this
blockchain url into our brownie smart
contract package well one of the easiest
ways is with an environment variable so
brownie actually already knows that
infuria is thing and can look natively
right away for inferior web 3
infuria
project id
and use our project id from infira if we
go to our project back in inferior
and we go to settings
you'll see the project id is a little
bit different than the whole url it's
just going to be this id right here
we can then copy this and paste this
right into our emv now that we have our
web3 inferior product id directly in our
project
if we do
brownie
networks list any network that infuria
has access to you'll see a little
inferior in colons here these are
networks that brownie will automatically
know about if we're working with
inferior so we can see here that ring b
is one of these inferior keys if we
wanted to deploy to ring b we could then
just run
brownie run
scripts deploy.pi
and then select the network with dash
network
rink b
now we're going to get an issue here
because remember account zero only works
when brownie works with a ganache cli we
have to use our actual private key here
and that's where some of those other
versions of working with private keys is
gonna come into play sometimes i'll even
add a get account function
so down here we'll do def
get account
and then in here i'll just natively
check if we're working on a development
chain we'll use account zero
and if not we'll use the method that
pulls from our config so we can check by
saying if
network
does show active
equals equals
development
then
return
accounts 0. network is another keyword
that brownie actually has
this network keyword allows us to
interact with different networks
now if it's not on the development
network we're going to pull directly
from our config
so we'll return
config
wallets
from key
and instead of doing account equals
account zero we can just do account
equals get account
now if we run brownie run scripts deploy
to pi network ringby it should pull
directly from our
config
file and great we can actually see
transactions being sent directly on the
rinkby chain
if we pull up ether scan
the ring be ether scan and we take this
transaction has and post it into the
bring to ether scan we can see this
transaction actually going through we've
deployed our simple storage contract and
it's initialized to zero
then we're going to go ahead and update
it and it gets updated to 15. now once
we've deployed to a blockchain
you'll see our build contract will
actually change
our deployments folder will have a new
deployment every time you deploy to a
blockchain brownie will actually save
that deployment so you can always go
back and say hmm where did i deploy that
or what happened with that deployment
you'll notice that it's separated by
chain id remember the chain id ring b is
four you'll also notice that none of our
development deployments are in here
again anything that's in this
development section isn't going to get
saved to the deployments area however
anything up here
and these ones will get saved and that's
going to be really powerful because we
can actually interact with contracts
we've already deployed onto a chain so
let's go ahead and even add
a new file in here
called
read value this function is going to
read directly from the ring blockchain
and it's going to read from a contract
that we've already deployed remember we
did something similar in web3.pi
by using the address
and the abi
we're going to do the exact same thing
but in brownie so in brownie again we're
going to do from brownie
import
simple storage
accounts
and config
we'll do def
read contract
and we'll just do pass for now
and then def main
is going to be read contract oops didn't
mean to do that down here and if we run
brownie run scripts
read value to pi
network rank v obviously right now
nothing's going to happen so how do we
actually interact with this simple
storage contract that we've already
deployed well this simple storage object
is actually just an array
if we were to print simple storage
let's see what we get
see we get this
brownie.network.contract.contractcontainer
object at here this object works the
same as an array we can access the
different indexes inside of it so what
if we do print simple storage at
position zero
you'll see we get this address here
and if we check on ether scan
we can see that this is indeed the
contract that we just deployed
ronnie knows that we just deployed it
because again
in our build section in the deployments
on the rink b chain which has the chain
id of four
we have this contract that we've
deployed now we can actually just
directly interact with this contract
we can do simple
storage
equals
simple storage of xero or if you're
always looking to get the most recent
deployment
minus one is a little bit easier if we
always do zero we're just going to get
the first deployment that we made and if
we make deployments later we're never
going to get past it
i want to always work with the most
recent deployment so i can just do minus
one remember how i said whenever we work
with a smart contract we need to know
its abi
and its address
well brownie already knows what the
address of this contract is it's got it
saved in this deployments folder
it also knows what the abi is because
when we compile it we get this big json
file and one of the first inputs that it
has is the abi so brownie automatically
knows what the abi is and what the
address is already
so then we can just go ahead and run
simple storage
dot retrieve
and print it out
and we should see 15 since we already
updated it
brownie run scripts
read value to pi dash dash network rink
b
and great we do indeed see 15. now that
we know how to write some scripts and
actually deploy things with brownie and
work with brownie i'm going to show you
one of the most powerful features to
also work with brownie typically we
write our scripts when we want something
to be reproducible and we want to do
something over and over again
deploying simple storage or reading of
value is something that we're probably
going to want to do over and over again
however maybe we want to work with some
of these contracts a little bit ad hoc
and get into a shell where we can
actually interact with these contracts
this is where the brownie console is
actually going to come into play and
make our lives a lot easier
so what we can do
is we're going to brownie
console
and what will happen
is brownie will actually kick us off
into a console it has all of our
contracts and everything already
imported
so if i run simple storage it gives me
back an array it's saying
great that's your simple storage
contract since we're working on a brand
new local test environment there are no
simple storage contracts deployed so
what i can do
is i can say account
equals
account zero
and we now
have
our account that we can work with
accounts is one of these keywords that's
automatically imported into our brownie
console
everything that is imported via brownie
in our script is automatically already
imported into this little shell here so
with that being said we can go ahead and
even deploy our simple storage contract
so we can literally take this line
copy it paste it in here
and you'll see exactly the same thing
that happens as if we ran our script we
get a little transaction hash here and
we get a simple storage
now
if i type simple storage the simple
storage variable now has a storage
contract here
if i type simple storage
you'll see i now have a contract in here
the length
a simple storage is now one because i've
deployed one simple storage contract
if i were to deploy it again
the length is now two
browning now knows i'm holding on to two
simple storage contracts and i've
deployed two simple storage contracts
i can then even do things like simple
storage
dot retrieve
and we can see
we start with zero i can go ahead and
even run
simplestorage.store
15
from
account
and we'll see we'll get a transaction
now if i rerun simplestorage.retrieve a
nice little hack here is in these shells
if you just hit the up key you'll
actually be able to go back in the
history of the shell so if i just hit up
twice here i can go back to this command
and i hit enter now we see the 15 is
here so the brownie console is a great
way to interact with these scripts in a
more ad hoc manner maybe we want to test
some weird functionality or maybe we
have some experiment that we want to try
it's a great way to really interact with
anything that we have in browning and
the other thing is we can do everything
that we normally do in python in here so
for example i could write print
hello
and it'll print out hello i could do
cat equals 1 plus 2
and i type cat and i get 3. so this
brownie shell is a python shell with all
of our smart contract features already
natively integrated and it's incredibly
powerful here
we go and quit it by doing quit so i
know we've learned a lot so far i'm sure
you're starting to see why working with
brownie is so much easier and makes our
lives as smart contract developers a lot
easier for testing them deploying them
and working with them
all right let's move on to our next
project is we're going to take the fund
me contract that we made recently in
remix and actually import that one into
brownie with this we're going to go over
a lot more of the advanced features that
brownie has to offer us and we're going
to get into some more sophisticated
testing and deployment mechanisms for
this so i'm going to make a new
directory
brownie
fund me
we're going to cd
into brownie fund me
and remember if you hit tab it will auto
complete i'm going to open this up in a
folder
again if code period doesn't work you
can always go up to file open folder and
do it like that we're in our brownie
fund me project and we're going to
initialize a new project
by running brownie
init
we're going to create a new contract
called
fundme.soul
this is going to be exactly what we had
before for our fund me contract so if
you have remix up great you can go ahead
and grab it or you can check the github
repository associated with this course
and just copy paste the code
now typically this is where in our last
project we just ran brownie compile
what happens if we run brown and compile
here brownie is going to give us this
error it's going to say hey this source
wasn't found so what's going on here
well remix understands that at chain
links slash contracts is an npm package
that it can import from however
brownie isn't aware of npm packages and
brownie can't actually download directly
from npm however brownie can download
directly from github so we have to tell
brownie where it should be downloading
these external these third-party
packages from so that we can use them in
our contracts here and while i'm in here
i might as well change the global
compiler version to 0.6.6
and we'll just change the compiler
version to carrot 0.6.6 so that our
linter is happy so we need to tell
brownie where to import these contracts
from from github instead of from npm
luckily there is a package out there
specifically created for downloading
chain link contracts the way that we can
tell brownie where to get these from
is in our browning config
so let's create our browning config
in here we're going to create a the pen
then sees section and this is where we
tell brownie the organization
slash repo name
at
version
that we want to download from
so so to get these chain link contracts
we can look up
chain link
brownie contracts
and we can use this repository to get it
so instead of downloading from npm we're
just going to download directly from
this github repo so we need to tell
brownie the organization which is going
to be smart contract kit
the repository name which is going to be
chain link brownie contracts
and then the version you don't always
have to use the latest version here in
fact we can go to the past nine versions
by clicking on the version history we're
actually going to be using 1.1.1
and yes it does look like the latest
version went backwards but as of a
recent release as a 1.2.0 version of
this package all the releases of
chainley brownie contracts is going to
match exactly the at chainlink contracts
npm tag so that's why it looks like this
is an earlier version so we'll say 1.1.1
so great so now brownie knows to
download this repository from github
once we do that everything everything in
this contract section will be available
for our solidity code to import and use
however that's not the final story here
we also need to tell brownie
what this at chain link thing means
because we're downloading from smart
contract kit slash chain link brownie
contracts ronnie's going okay cool well
what's the sat chain link thing so we
need to tell brownie whenever we're
using at chain link we're actually
referring to this import so we need to
tell the compiler this
so let's add a new section we'll say
compiler
when it compiles sulk
we need to remap
at chain link
say whenever you see at chain link here
it means
we're referring to this package
so compiler soccer mappings at chain
link
is equal to this package up here now
let's go ahead and try to compile
perfect we see here that it compiles
successfully and if we look at our build
folder
in the contract section we now have this
new folder called dependencies
and if we even expand this a little bit
we can see
it says dependencies smart contra kit
chain link browning contracts at 1.1.1
and this is what it downloaded from that
github repository it downloaded
aggregator v3 interface and smart math
chain link because we're using both of
those files in our solidity code all
right great so let's write our first
script to deploy this to a development
ganache chain to brownie's built-in
chain
let's do this
so in scripts let's go ahead we'll
create a new file let's go ahead and
build a simple deploy script to work
with rink b and then we'll actually
learn how to deploy this to our own
local ganache development chain so let's
build our deploy script so in scripts
we'll do new file
deploy.pi and we'll start by doing def
deploy
fund me
then we'll do pass for now
and then we'll do our entry point of
deaf main and then we'll call
deploy fund me in this file of course
we're going to do from
brownie
import
fund me
so we can actually use this and let's go
ahead and build this deploy fund me
function so first we're going to need to
get an account
and same as last time we used a function
called get account which would know to
switch back and forth between if we were
on development or if we were with an
actual testnet that we could pull from
our config we can actually once again
copy that function
and use that and use that in our script
here so once again we can use that get
account function that we had before what
i like to do with this get account is
add it into its own file called helpful
scripts
so what i'll do is create a new file
called helpful
scripts.pi
and in here i'll add that getaccount
function right so literally just pasted
it from our last project and just a
quick recap on what this is doing
is we're saying if the network is in
development we're going to use the
accounts 0 syntax otherwise we're going
to pull from our config
and of course we're going to have to
from brownie
import network
config
and accounts
and then of course in our browning
config we're going to have to add
wallets and from key so let's go to our
config
we'll do wallets
from key
and we'll add
our private key environment variable
setup
which of course means that we're going
to have to set dot env
to dot e and v and we're going to create
new file dot amv
and we'll paste
the exact same values from our last dot
emv so it's going to be our private key
and our project id kind of just a lot of
the basics of the setup here
but now that we've added this get
account to its own script how do we
actually use that in our deploy script
depending on the version of python that
you're in you might actually have to
create a new file first named underscore
underscore init underscore underscore
dot pi
you might not but just in case let's
make it here because it doesn't hurt and
with this now python knows that it can
import from other scripts and other
packages
in this project so now we can do from
scripts
dot helpful scripts
import get account so we're importing
that get account function
from our helpful script here and we're
gonna make this get account function a
little bit more robust a little bit
later but for now it'll work perfectly
for what we're looking to do now we can
just run our typical deploy function
funny we'll do the fundme contract
equals fund me
dot deploy
and of course we'll do from
account
because again since this deploy is going
to make a state change to the blockchain
we always need to do a from account
section here then we can even do a
little print
we'll do a print f here
so we'll say
contract
deployed to
fund me
dot address
this is how we'll get the address of our
fund me and great we can even go ahead
and try this out right now remember
you'll need some testing
ethereum in your metamask
brownie run scripts deploy.pi
dash dash network
rank b
and
perfect contract deployed here it is
we can even go to
bring the ether
scan again
and we'd see the contract right here now
this is great and all but if we look at
our contract
it's kind of this blank jarble of
bytes here right nobody can actually see
this contract and and easily interact
with it and we want to make our
contracts easy to interact with what we
can do on etherscan is verify and
publish our smart contracts to verify
our smart contract all we have to do is
hit that verify button
we'll choose our solidity compiler type
which we know is going to be
0.6.6
and we know we're working with the mit
license here
now to continue we would then have to
add in all of the
rest of these pieces we'd have to do
optimization which is going to be yes
we'd enter our solidity contract code
below which importing fund me like this
wouldn't actually work
because etherscan doesn't know what at
chainlink contracts is
so we would have to
copy paste the code
from these imports to the top of our
contract here removing these imports and
copy pasting the code associated with
those files is known as flattening and
this is an important concept for
verifying our smart contracts on
platforms like etherscan
however brownie has a really nice way to
get around this actually what you can do
is go to their main site etherscan.io
you can sign in and sign up and get an
api key i've already signed up so i'm
going to go ahead and sign in here
log in and what we can do is we can go
to my profile
and scroll down to api keys
and this is where we can create an api
key for us to interact with and
programmatically verify our smart
contracts on etherscan i've already got
one here but all we need to do is hit
add
we'll give it a name i'll call it verify
browning continue and we've created this
new api token that will allow us to
verify our smart contracts what we'll do
to use this in brownie
is we'll copy this api key
and we'll move back to our scripts here
we'll set this api key as an environment
variable so we'll do export
the name of this is etherscan
token
and we'll set it equal to that key that
we just got now to verify this all we
have to do then is once we deploy this
contract we'll tell brownie whether or
not we want to verify the contract
so after
our dictionary here
we'll do comma
publish
source equals
true we're saying yes we would like to
publish our source code
now if we rerun this script
let's see what happens again remember
we'll do browning
run
scripts
deployed up high dash dash
network space
rinkaby
and says fund me has been deployed to
here
now we're going to say waiting
for api
rink b dot etherscan.io to process
contract
and we're submitting our code for
verification here and it'll say
verification pending verification
complete pass verified it'll say where
the contract has been deployed and
what's been done with it
now if we go back to ether scan again
we're going to have to go back to rink
be ether scan because we deployed this
to rank b and we paste this in
we now have this little check mark
associated with our contract
and if we click contract we can see all
of the code in here
for our contract
we have contract fund me
payable you need to get more everything
that we defined in here and if we scroll
up we can see that they did indeed
flatten this contract right they
pasted that aggregator v3 interface
import
and they also pasted that library safe
math chain link now that's verified we
can even read the contract see the
different public variables in here such
as the owner get version get price and
all the exact same buttons that we saw
in remix this read contract section is
for all these view functions right the
ones that aren't going to be making a
state change
right contract
is going to be for when we want to call
something like fund or withdraw and we
could even go ahead and interact with
this so for example we could connect to
web3
metamask
okay and it would automatically get
connected to our metamask here then we
could call fund and withdraw just like
we did in remix if you want to give it a
shot go for it all right we're back in
our code editor after successfully
verifying one of our smart contracts on
etherscan now just a quick note
sometimes the verification process can
be a little bit touchy and for version
of solidity 0.8.4 there's currently a
bug that makes it verifying a little bit
tricky but it's being worked on so don't
be discouraged if it gets a little bit
funky so this is great that we've
written a deploy script for deploying
directly to ring b however as you know
we're always going to want to be able to
deploy to our own local blockchains or
or brownies built-in development chain
so we can test a lot quicker and that
yes so that we can write some tests but
we have a little bit of an issue here
the first issue being that our fundme
contract currently has an address
hard-coded to work with the rink be
chain so in fact the way it's written
right now it's going to be hard to work
with any other chain other than ring b
the second bit is that these price feed
contracts don't exist on a local ganache
chain or a gnost chain that brownie
spins up there's two ways we can get
around this we can do what's called
forking and work on a forked simulated
chain
or we can deploy a mock or deploy a fake
price feed contract on our ganache local
development chain deploying mocks is a
common design pattern used
across all software engineering
industries and what it applies doing is
deploying a fake version of something
and interacting with it as if it's real
so again right now if i run brownie
run
scripts deploy.pi and i don't set this
network flag we're going to actually
have a default spinning up a ganache
chain it's even going to try to verify
which it's going to run into an issue
because we can't verify on a ganache
chain so we have a couple issues that we
need to address here in order for us to
get this to work on a ganache chain
similar to how in this get account
function in our helpful scripts
we do a little bit checking we say hey
if we're on a development network
use this development accounts version
otherwise
pull from our config
we can do that exact same mentality but
with working with these marks so the
first thing that we need to do is we
need to parameterize our fund me
solidity smart contract
so that we don't have this hard-coded in
here anymore so what we can do
is right when we deploy this contract
we'll tell it what price feed address it
should use right when we call our deploy
function here instead of having it hard
coded
and we can add this parameter to our
constructor we'll say
address
price feed
as an input parameter and whatever input
parameter we use here is going to be our
global price feed address so instead of
us creating
these aggregator v3 interface contracts
right in the functions here we're just
going to create a global one so we'll
say
aggregator
v3 interface public
price feed
and right in our constructor
right when we create this we'll set
price feed
equals
aggregator v3 interface
price feed
and now what we can do is we can just
delete this part because as you can see
this is doing the exact same thing
is up here this is doing aggregator v3
interface price feed equals aggregator
v3 interface and then the address here
and we're going to do the exact same
thing but in our constructor meaning
right when we deploy this contract so we
can delete this
and we can delete it here as well in our
get price function we can even verify
this with brownie
compile
great looks like it's compiling
perfectly
now
our deploy function is going to need to
look a little bit different we're going
to need to pass
the price feed address
to our fund me contract to do this all
we'd have to do is paste
that address before we have our from
account variable here
so this is how you can actually pass
variables to constructors anything
inside this constructor function you can
pass through brownie in our deploy
script here so great so we could 100
always just pass this rink b address
here but that's not really going to
solve our problem obviously right the
problem is that the problem right now is
that we always have this ring b address
when we say if we are on
a persistent network like rink b
use the associated
address
otherwise
deploy mocks and i know we've been
talking about mocks we'll get into them
in a second but let's first set this one
up here so we can check what network
that we're on again by importing from
browning this network bit and we can say
if
network dot show
active
does not equal
development then
we'll say price feed
address
equals
this address here and we'll just pass
this price feed address now this still
doesn't solve our issue because we're
just always passing this the rink be
hard-coded piece here so what we want to
do is parameterize where we get these
addresses from so instead what we can do
is in our browning config we can add
different addresses for different
networks so right underneath our dnv
we'll add a new section called networks
and we'll do one called rink b and we'll
say the fusd
price feed
address is going to be
this price feed address now what we can
do in our deploy script
is we can say
if we're not on a development network
let's grab the address from our networks
section this way we can define
different addresses for this price feed
across different networks so we can add
we could add a coven section
we could add a mainnet section any other
networks that we want to work with all
we need to do is add add these flags for
those contracts so back in our deploy
now we can see the price feed address is
going to get pulled from the config
instead so we'll say config and
this means we're going to import config
or brownie
say config of networks
based off of the network dot show
active
and then we'll use the fusd price feed
flag here
perfect
so this little if statement is going to
say hey if we're not on a development
network
pull the address right from the config
and this will make it so that we can
deploy to really anywhere that we want
to deploy to but what if we are on a
development chain well what do we do
then we can say else if we're not on a
development chain we're going to have to
deploy a mock so right now
on all these live networks that we're
working with there is a version of this
price feed contract this price feed
address our development chain obviously
there won't be one because it's going to
start off as blank so what we can do is
we can deploy our own version of the
price food contract this is known as
mocking and we can interact with it
accordingly in order for us to deploy a
price feed contract ourselves we're
obviously going to need to have the
solidity code associated with it so what
we can do
is in our contract section we'll create
a new folder called test
when you create a test folder in your
contracts folder this is typically where
mock contracts are going to go and we'll
create a new file
called mock
v3
aggregateor dot sol
and this is where we'll add the code for
us to deploy our own price feed now i'm
going to show you another repository
pretty soon called the chain link mix
that we're going to work with
for now if you're looking for one of
these mocks i highly recommend just
pulling it from this chain link mix
repository so we can grab it by going to
contracts
test
and grabbing my aggregator dot soul we
can just copy this whole code
and paste it into our mockv3
aggregator.sol this has all the same
exact functions as a real price feed
contract such as decimals and latest
answer which are going to be two of the
ones we use the most we can also see its
constructor here
these are the variables that it takes
whenever this contract is deployed
it takes a decimals and an initial
answer decimals is of course going to be
how many decimals that this contract
should have an initial answer is going
to be its starting value like 2000 for
example once we have this contract in
our test section we can of course run
brownie compile and brownie will go
ahead and compile this mock v3
aggregator as well because remember
brownie compiles any contract in this
contracts folder let's go back to our
deploy script now that we have this mock
v3 aggregator in here now we can do is
we can do a little else here
saying okay well if we are on a
development chain let's do something
let's deploy these mocks so let's do a
little print statement here a little
printf saying
the active network
is
we'll do network
dot show active
another print statement print f saying
deploying
mocks dot dot dot oops i need a little
closing there
and this doesn't need to be print f
it can just be a regular print and then
now the same way we import fund me we
can import mach v3 aggregateor
we can just deploy this contract the
same way we deploy all of our other
contracts so we'll do mach v3 aggregator
dot deploy and as we just learned we
have to add the parameters the
constructor takes which is going to be
decimals and initial answer
so maybe we'll set decimals to 18 and
then maybe we want to set the initial to
answer to 2000 so two one two three one
two three four five six seven eight nine
ten one two three four five six seven
eight comma and of course since we're
deploying we've got to do a from
and we'll use our account here
we'll do another print
saying
mox
deployed and of course we're going to
need to get this mock v3 aggregator's
address so we'll do
mock aggregator
equals this and we'll set
price
feed address
to equal
our mock aggregator dot address
and now we're development or live
network agnostic if we deploy this on a
live network we'll use the address from
our config otherwise we'll use a fake
aggregator contract that we've deployed
let's go ahead and even try this on a
development network
so we can do brownie
run scripts deploy.pi we don't need a
network flag here we'll hit enter it'll
spin up the ganache
and we even will deploy a mock
aggregator contract first
and then we'll do our fund me part of
course we are running to an issue
because we're trying to verify a
contract on a chain that doesn't exist
etherscan doesn't know about our local
gnost chain so to fix this
instead of doing publish source equals
true we can have this published source
be again based on what chain that we're
on so we'll go back to our browning
config and for rank b
we'll say verify
will be true but for development
we'll say verify will be false and back
in our deploy script we now say publish
source
is going to be pulled from our config so
again we'll do config
networks
network dot show active
and then we'll do dot get
verify
this dot get verify
will make our lives a little bit easier
if we forget to add verify in here you
could still do like this
like verify but you run into some index
errors if you forget to actually put the
verify so sometimes i get lazy and uh
it's just a little bit nicer like this
now if we run this again
deploy.pi
we'll spin up our local ganache we'll
deploy a mock price feed contract
and then we'll deploy our fund me
contract
and it completes successfully so this is
awesome we have a way
our fund me contract that uses a price
feed contract to our own local
development environment with a mock aka
a fake price feed contract this is
awesome now this is great but our deploy
script is starting to look a little big
and a little clunky so let's actually
clean this up to make it look a lot
nicer the first thing that we want to do
is we want to fix this this big 2000
number just looking at right away i'm
not exactly sure how many zeros it has
so to make this look a little bit nicer
and more readable we can once again call
on our friend web3.pi from
web3
import
web3
and down here we'll do web3.2
way
2000
comma
ether this two-way function will just
add 18 decimals to this 2000 so now this
is much more readable that the initial
value for this is going to be 2 000. the
next bit is that we're always deploying
this mock v3 aggregator here and if we
already have a mock deployed to whatever
network that we're working on we don't
need two marks here so what we can do
then is right before
we deploy this mock is we can do a
little if statement
we can say if
the length
of our
mock v3
aggregator
is less than or equal to zero
only then will we deploy
this mock v3 aggregator remember we can
check the length of our v3 aggregator
because this v3 aggregator is just going
to be a list of all the different v3
aggregators that we've deployed now
instead of using mock
aggregator.address we can just
use mach v3 aggregator
minus one dot address so we're just
saying okay great just use the most
recently deployed mock v3 aggregator
and then of course we don't we no longer
need to set this as a variable and that
looks a little bit cleaner and we'll
make this a little bit more efficient so
this deploying mox bit though is going
to be something that so this deploying
mox bit though is going to be something
that we're actually going to do
relatively frequently let's even move
this print statement up here so instead
what i like to do is put this whole mock
deploying bit in its own function in our
helpful scripts so let's open back up
our helpful scripts we'll do a new
function called def
deploy mocks
and we'll just paste that code in here
of course this means that in our helpful
scripts we're gonna have to import
mock v3 aggregator we'll also have to do
from web3
import
web3 instead of account we'll just use
this get account function now back in
our deploy script
we just delete this whole part
replace with
deploymox
and then import deploymox from our
helpful scripts
and then we can also delete this import
now let's remove some of these comments
if you'd like this is starting to look a
lot more sophisticated and this is great
because now we have a way to deploy base
off if we're on a live chain or a
development chain and then one more
thing i like to
do so that everything is parameterized
i like to set these as static variables
in the top of our helpful scripts
so i'll set decimals
equals 18
and then i'll set starting
price
equals 2000 and then i'll have
mock v3 aggregator to deploy to decimals
web 3.2 way
to
starting price here
so no so let's say now that i wanted to
deploy this to my own ganache instance
well what we could do is we can open up
our ganache here we'll do quick start
and we'll just quickly create our own
ganache blockchain in our script let's
go ahead and just run this deploy script
again
let's see what happens instead of
brownie spinning up its own ganache here
it says attached to local rpc client
listening ad and then this address here
brownie is smart enough to detect if
you're running your own ganache instance
here and will automatically
attach itself to it knowing that that is
going to be a development environment if
we go to our ganache we'll see
we have two transactions which are going
to be
contract creations we're going to create
a price feed contract and then also our
fund b contract so this is great this is
great for testing quickly and locally
but there is an issue with this for
development networks again brownie
doesn't keep track of those so in our
build folders if we go to deployments we
only are saving stuff from the rink b
chain here so we would need to tell
brownie hey there's another network that
we want you to work with and we want you
to remember the deployments to that
chain so what we can do is we can add a
new network to our browning networks
list remember
in brownie
networks list we have all these
different pieces in here these are the
ones that brownie is going to not
remember and these are going to be the
ones that brownie remembers so let's say
we want to deploy to a grenache chain
and we want brownie to remember those
deployments well we can add a network
here and this is going to be how we add
any blockchain that we want any evm
blockchain like avalanche like polygon
etc to add a new network to the brown
networks is we'll run
brownie
networks add
we'll choose development or ethereum
we're going to choose ethereum because
we want this to be a persistent network
we'll do ethereum
we'll give it a name i'm going to call
this ganache
local
we need to give it a host
aka an http address which
we know
is right here
and then i'm just gonna
make this lower case
and then a chain id
which for this we know is one three
three seven
hit enter
now if i do brownie networks list i see
a new blockchain called ganache local
and this is going to reach out to our
ganache ui or our ganache command line
depending on what we're running now just
a note we are going to be deploying to
this ganache ui or ganache cli
a lot for the rest of this lesson so
please keep your ganache instance
running now what i can do
is i can run brownie
run scripts deploy.pi
network
ganache
local let's see what happens of course
we run into our first issue ganache
local isn't development so it's going to
go ahead and try to pull from our config
file we don't want this we want to
actually deploy mock for our local
ganache if a mock hasn't been deployed
so what we can do
is we can extend our definition of what
a development environment is in our
helpful scripts we can add a flag in
here we'll say local
blockchain and vi romance
equals and this will be a list we'll say
development
of course will be one but we can also
say
ganache
local
will be another and now we can import
this local blockchain environments into
our deploy so from at the top from
scripts.helpful scripts
do a comma here
paste that and save
mine gets reformatted which is really
nice and instead we'll say if
network.showactive
not in
local blockchain environments
then go ahead and pull from the config
what this is saying is it's saying if
whatever network that we're on if it
isn't development
or ganache local
then go ahead and use a config
if it is one of these two
we're gonna go ahead and deploy a mock
here now that we have that let's try
this again ronnie run scripts
deploy.pi dash dash network
ganache
local and we run into a different issue
we're saying hey you don't actually have
enough gas well
why is this let's look at our get
account function aha this one is also
looking directly for this development
chain this one will say if
network.showactive
is in
local blockchain environments then
return accounts zero so we're saying if
the network we're working on is
development
or our ganache local then just return
accounts zero so let's try this okay
we're getting closer now we're running
to this key error of ganache local
well we do know how to fix that as well
in our config we'll add this new network
we'll say ganache local
and we'll set verify
to false so let's try this one more time
perfect now mocks have been deployed and
our fundme has been deployed
and if we look in our build folder in
deployments we now have a new chain id
for one three three seven for saving
these deployments and it looks like in
our ganache chain we have these actually
saved in here which is great now an
important thing to note if you were to
close this or delete this ganache chain
all of your contracts will be lost so
you won't be able to interact with them
again to account for this you can always
delete 1337 and delete the entries in
one three three seven from your map.json
or if you're fine deleting the whole
build folder you can delete the whole
build folder so now that we've deployed
this let's actually write a script to
interact with this so let's create a new
file we'll call it fund and
withdraw
dot pi
and this will be the script we use to
fund and withdraw so let's create a
function called
fund we can say fund me
equals
the most recently deployed
fund me we have to do from
brownie
import fund me we're gonna have to get
an account since we are gonna be making
some state changes and we just have this
equal to get account
and we can do from
scripts dot helpful scripts
import
get account
let's get the entrance fee so we can
figure out how much we want to fund
actually sorry since this is going to
resemble that fusd price feed it
actually only has eight decimals two one
two three four two thousand and one two
three four five six seven eight
the reason we want to do it like this
too
is because
in our get price function we know that
it only has eight decimal places so
we're multiplying it by an additional 10
here
we want to resemble that as well so
we'll do eight decimals starting price
of 2000 with eight decimals here and for
our mock v3 aggregator we're just going
to use those exact values and we're not
going to do the web 3 converting we're
just going to make it exactly those
hard-coded values now we're going to
want to get the entrance fee so i've
gone ahead and actually added a function
called get entrance fee to our contract
to make our lives a little bit easier
here i'm going to recommend that you
take a look at this and then
type it in yourself or you just copy
paste it from the github repository so
that we can use this get entrance fee
because it's just a whole bunch of math
here so back in our fund and withdraw
what we can do then is we can do
entrance fee
equals
fund me dot get
entrance fee
excuse me get interested
and we can even print out this entrance
fee just to see if we're doing it right
but first we're going to want to run
brownie
run scripts
deploy
network ganache local because we changed
our fundry.soul
all right great
and now we can run brownie
run scripts
find and withdraw
network
local
and whoops i need a main function so
we'll do def main
fund in here
and let's rerun this
and great we can see this is the
entrance fee do a little print statement
here printf saying the current
entry fee
is
entrance fee
we'll do a little print saying
funding
and then we'll call fundme.fund
and of course we're going to do a from
account
and we're also going to send a value
of
entrance fee
any low level transaction data that we
want to send with our transactions and
function calls we'll add in this little
bracket piece here let's set up let's do
brownie run scripts funder withdraw
again
and great it looks like it's going
through perfectly
awesome let's also do a withdraw
function for the owner to withdraw
we'll say fund me equals fund me
minus one
do account
equals get account
and then we'll just call fund me
dot withdraw
from
account
and then right after fund is called
we'll have withdraw be called and our
main function here
let's go ahead and try this
brownie run scripts
find and withdraw
network
ganache local
this is our funding script
our funding transaction going through
and then our withdrawal transaction
going through perfect so it looks like
our approximate functionality here works
great and this is a script that we can
run on a main network if we'd like
now again it's still much better for us
to run so now we're going to move into
actually
writing those tests and for these tests
we're going to want to quit our ganache
ui let's go ahead and write some of
these tests create a new file
called test
fund me
dot pi we'll quickly speed through this
test because we're not going to learn
too much new here keep in mind when
we're on this test we're going to want
it to be able to work independent of the
network that we're working on so let's
just keep that in mind let's do a test
just to see if we can fund a withdrawal
so we'll do def test
can fund
and
withdraw
and we'll do basically exactly what
we've done before
do account equals get account
of course
we'll do from scripts
that helpful scripts
import get account then we'll want to
deploy fund me and we can even just use
our deploy fund me script in our
deploy.pi so we can do from
scripts
dot deploy
import
deploy
fund me in our deploy fund me at the
bottom we'll just say return
fund me so that our test can now have
this fundme contract for it to work with
so now we'll say fund me
equals
deploy
fund me
grab the entrance fee
which will be equal to
fund me dot get
entrance fee
and then let's go ahead and fund it so
do transaction equals fund me
dot fund
and we'll call from
account
we'll do value
entrance fee
we'll do tx.weight one
we'll do an assert here we'll do assert
fund me dot address
to amount
funded
it's going to be account dot address
it's going to be equal to the entrance
fee
so we want to check
that our address
and the amount that we funded is being
adequately recorded and then we'll do
transaction two will be fund me
dot withdraw
from
account
tx2.weight
one
and then we'll assert
fund me dot address
to amount funded
account dot address
equals zero
and let's go ahead and run this test so
we'll do brownie
test
and perfect looks like it's doing well
now you may be wondering why sometimes
we use the dash dash network flag and
sometimes we don't in our network
section brownie automatically picks a
default network to use and the default
is always set
to development
however we could set this to be anything
that we wanted we could set the default
to be ganache
local we could set it to be rink b
whatever we want it here whatever you
set for the default in your brownie
config is what the network will be
defaulted to so right now when we run
brownie test this is equivalent to
running brand test dash dash
network
development we can even go ahead and run
that too now we could also run this test
on rink b and we will in a second but
oftentimes we don't want to test all of
our functionality on rink beat and on
live networks because it's going to take
a long time for them to run so sometimes
we only want to run tests
on our local chains well how do we do
that we can use pi tests skip
functionality to do so to work with pi
test we're going to first need to
install it so go ahead and run pip
install pi test to demonstrate this
let's create a test that makes sure only
the owner can withdraw and nobody else
can so we'll call this def test only
owner
can
withdraw
to skip this test if we're not on a
local network we'll first check the
network we'll say if
network.showactive is not in
and yep probably would have guessed it
we're going to pull this local
blockchain environments in from our
helpful scripts so we'll do comma local
blockchain environments
and we're going to say if the network
dot showactive
is not in this list of local blockchain
environments we're going to do pi
test.skip
and say only for local testing
of course we're going to import network
and we're also going to import pi test
now if i try to run
this test here
with brownie
test
dash k
dash dash network rinkeby it should skip
perfect and we do see with this s here
meaning that it's skipped this function
if we run this
with dash network
development
it should go ahead and run this and it
will pass because nothing happens in
this function and it does perfect let's
keep going so now we'll say account
equals get account
we'll say fund me
equals
deploy
fund me
and now let's get a different account
to try to call the withdraw function
so we'll say bad actor
equal and this will just give us a blank
random account
but we do have to import accounts
from about here
now we want to test to see that them
calling this withdraw function actually
reverts them and causes an exception
because if i try to do
fund me
dot withdraw
from
[Music]
bad actor right now
what do you think will happen well that
well we know in our fundme.soul our
withdrawal function has the only owner
modifier so technically only the owner
should be able to call this function
so what happens actually we don't even
need this account get account bit let's
just go ahead delete that so what
happens if somebody else tries to call
this withdraw function well let's go
ahead and test this we'll do browning
test
dash k
test only owner can withdraw
hmm and you can see we're getting this
error here writing
browning.exceptions.virtualmachineerror
revert from this fundme.withdraw well we
want this to happen we were expecting
this to happen so how do we test that we
want this to happen well we just need to
tell our test that we want this to
happen
so first we're going to import from
brownie this exceptions
package this way we can tell our test
exactly what exception we're expecting
to see then we'll say with
pi test
dot
raises
exceptions dot
virtual machine error
fund me
dot withdraw
and then we'll just actually we'll just
copy this line down here
now what this is telling our test is
that if this reverts with this virtual
machine error that's good we're saying
we want you to revert when you try to
call this line so if we delete this line
and hit up and try to run this again
we can see that it now passes and this
is exactly what we're expecting so this
is awesome all right we've learned a lot
of fantastic tools for working with
brownie here now the last version of
testing that i want to show you how to
use is mainnet forking maintenance
forking is incredibly powerful when
we're working with smart contracts on
mainnet that we want to test locally so
let's talk about forking for a minute so
on the left here i have a blockchain
right an example of a blockchain this is
going to be like a test net
like rinkaby
or something like mainnet right this is
going to be a blockchain that we
actually deploy to
now there are a whole bunch of blocks in
here right and there's a huge chain that
we can actually work with all this
information is public information right
this block is going to have like
transaction
transaction
transaction
it's going to have you know each one of
these blocks is going to have a whole
bunch of transactions and all this
information is here in addition to all
these transactions it's going to have
price feed contracts
ave contracts
you know et cetera it's going to have
all these different contracts in it so
hypothetically if it's already there we
should be able to basically copy this
all this whole blockchain and do some
simulations ourselves
and that's exactly what forking does
a forked blockchain literally takes a
copy of an existing blockchain on the
left here and brings it into our local
computer for us to work with we actually
have control of this blockchain since
it's going to run on our local computer
similar to ganache now all the
interactions that we do on this local
blockchain are not going to affect the
real blockchain because it's our local
chain right it's a simulated blockchain
but because it's simulated we can go
ahead and interact with price feeds we
can interact with avid we can interact
with all these different contracts that
are already going to be on chain
maintenance fork is a built-in part of
brownie and also pulls from inferior the
same way it works with rink b and coven
and everything else we can start to
interact with the mainnet fork contracts
the exact same way therefore so we can
take this whole ring big section
copy it
paste it
and we'll just change this fusd price
feed address
to its mainnet address so we'll go to
docs.chain.link
ethereum price feeds
get fusd here
copy that
and we'll paste it into here and we'll
change this to mainnet fork and since
this is going to be a fork of course for
verify we're going to do false
now if we try to run one of our scripts
like brownie run scripts deploy.pi
network
mainnet fork
you'll see we'll actually run into an
issue here it's saying insufficient
funds for transfer in our deploy script
when we do our get account and our
helpful scripts
right now we're using accounts.ag config
while it's from key yes it's going to be
our account which right now has zero
money in it on mainnet so brownies right
away gonna say hey you don't have any
money on mainnet what's the deal so we
need to tell brownie that when we're
working with mainnet fork it should
create us a fake account with a hundred
ethernet however
we don't want it to deploy a mock
because the price feed contracts already
exist so we don't want it to deploy a
mock but we do want it to get us an
account here so typically what i like to
do
is i'll add another variable here and
i'll call it
forked
local environments
and i'll add
maintenant fork in here and i'll use
this now as part of my if statements
so i'll say if network does show active
in local blockchain environments or
network dot show active
in forked local environments then we're
going to go ahead and return account 0.
however
in our deploy.pi mainnet fork is not
going to be in this local blockchain
environment so we will just get our
price feed from our config so now if i
run this maintenance fork again now if
we run this you'll see we'll still get
an error we'll get list index out of
range so brownie's built-in forking
mechanism doesn't actually come with its
own accounts here however it has these
issues so what normally i like to do is
i like to create my own custom
maintenance fork right in browning the
way we can create our own development
custom network is by using the brownie
network's add key so
we do brownie
networks
add
we'll make this a development network
instead of a persistent network
and we'll call this
mainnet fork
dev
to set this up we'll do a ganache cli
so we'll say the command to run this
fork is going to be ganache cli
the host is going to be the same as
always http
dot
colon slash 127.0.0.1
fork is going to be equal to and this is
where we just put https
mainnet
dot infira dot io
v3
slash
web 3
infira
project
id
now don't hit enter quite yet i'm going
to explain a couple things
so this single quote means
run this as is if we run this without
the single quote our environment
variable would get actualized here and
we'd always have to use whatever our
current environment variable is so we
want to have this little semicolon here
then we would do accounts equal 10
this tells brownie for us to set up 10
fake accounts for us we'll give it a
mnemonic
of brownie so we'll say great make those
accounts just have a new monica brownie
and we'll do a port equals eight five
four five now once again don't hit enter
quite yet i do wanna explain one other
thing so this is great for working with
inferior and forking from inferior
however i have to note that performance
wise forking forming fura has pretty
much always given me an issue
so i prefer actually to fork from this
application called alchemy and in fact
if you'd like you could set up all of
your networks to work with alchemy by
modifying them i'm going to go ahead and
sign in here and we're going to give it
an alchemy url instead of an inferior
url so i'm going to go ahead and create
an app
i'm going to call this fund me
demo
description will also be a fund me demo
via development environment on the
ethereum mainnet let's create this we
can now view the details of this we'll
go to view key and we'll copy
this http address
and we'll move back over here and for
forking
we can just
delete
everything next to this fork
and we'll just paste that in here
instead and let's go ahead and hit enter
you'll know you've done this right if
you can see something like this mainnet
fork dev has been added oftentimes in my
example i will actually just delete
maintenance fork
and have mainnet fork dev be my default
for maintenance for but for us we're
going to go ahead and do mainnet fork
dev
so in our config
we're going to change mainnet fork to
mainnet fork dev
so since we're giving this a different
name
that means in our helpful scripts
we're gonna have to have do a comma here
and say mainnet fork
dev all right great now our get account
should return accounts 0 for maintenance
fork dev and it should actually work so
let's run our script again brownie run
scripts
deploy dash dash
network
mainnet
fork dev
and perfect we're running our
maintenance fork dev
and it is running successfully
now we should also be able to test
exactly the same way let's look at our
test real quick
test fund me and see okay cool we're
going to be skipping this one since main
at fork forkdev isn't in the local
blockchain networks but this should work
perfectly and then oftentimes in my
tests here i'll actually do like a
little plus
100 or something for entrance fee just
in case i need like a little bit more
money for whatever reason so now if we
run founding test dash dash network
mainnet fork dev
we'll see that this does indeed pass and
this is awesome so this is fantastic
incredibly powerful project here now
we're going to teach you how to actually
share your code and enter the world of
open source and decentralized code the
way the world works when sharing code
and sharing ideas and collaborating
together is they use what's called open
source git repositories github is an
example of one of these git repositories
that we can use to share our code and
it's one of the dominant ways that smart
contract engineers share ideas and share
code we are now going to learn how to
add our code to github and then we can
even share the code and show the world
what we've built and what we've done
this isn't going to be a full end-to-end
git course however there are some links
in the course repository that will show
you how to work with git work with
github and work with version control so
the first thing that we're going to do
is we're going to come to github and
we're going to sign up for
a service
add our email
create a password
enter your username no now we'll go to
our email to verify it
continue we're going to be working with
some collaborative coding we're going to
choose the free edition and perfect we
are now in github now that we're in
github we're going to create our own
first open sourced repository so we're
either going to hit this plus button
here or create repository let's choose a
repository name for this we'll give it
the same name as our main folder so call
this brownie fund me give it a
description maybe smart contract
application
and we'll hit create repository this is
where we're going to upload our code to
share with the world back in our vs code
now we're going to send this folder to
that repository first thing we need to
do is installing git there are a couple
different ways to install git depending
on the version that you're on we'll put
this link in the description to our
course to actually install git once you
have it installed you should be able to
run git dash dash version
and see a git version here now we're
going to initialize our repository in
here by doing git init
we're going to choose a branch name
we're going to call it main
we'll go ahead and add our username and
email to our git config user dot
name
quotes
free
code camp
video
git config
user dot email
free code
camp
video gmail.com
now we're going to do a couple things to
push all of our code to github here
however remember we do not want to push
our dot env pieces up here so we can do
a couple of things we can a we can go
ahead and delete this of course but we
can also add in our dot git ignore file
a dot env this will help us so that we
don't accidentally push our dot env file
to github we can choose what files we
want to push by doing git
add and then a period and if we do get
status
it will now show us all the different
files that we have staged to push to
github if we look in here we see we have
git attributes git ignore browning
config
fund me some contracts some scripts but
we do not have that dot emv file
if you were to remove dot emv from dot
git ignore and you ran git add dot again
and then we did get status
we now see the dot env in here
we do not want this in here so we can do
git
remove dash dash cached
dot e b
we'll add
dot env
back to our dot get ignore file
and then we'll run git status again and
then we'll run git add period
and then get status
and great we do not see that dot env in
here so that's very good now we'll
commit this by git
commit
minus m
first commit
and now we can add
this folder to our github back in our
github there's a little line here which
even tells us how to do it we're going
to copy this line right here
git remote add origin https free code
camp brownie fund me i'm going to copy
that
paste it in here
hit enter and now we can just do this
second line
git push dash u origin main we'll do git
push dash u
origin main we get an output like this
and if we go back we'll now see all of
our files and folders in here now i've
already added my email and password in
here but instead of this you'll probably
get github asking you for authorization
you can just go ahead and put your
github username in and your password in
there if your username and password
doesn't work you can come into github go
down to settings
scroll down to developer settings
personal access tokens and generate new
token we'll call this f
brownie and we'll want to give it at
least repo authorization here and we'll
hit generate token
and instead of using your password you
can go ahead and use this github token
amazing and you now have your first
github repository
we could even come in here add some
topics
like solidity
chain link
python
brownie
etc so that we know what our file is
about and this is incredibly exciting
now i'm gonna even encourage you
to pop onto twitter and share your
excitement
i just made
my first first
at
thanks to at free code camp
at
solidity
brownie s
at chain link if you want to tag me you
can also tag at patrick alpha c
and pop your repo in there go ahead and
hit tweet the community absolutely loves
hearing about all the fantastic things
people are doing in this ecosystem so be
sure to reach out have fun and engage i
know we've gone over a lot here but
let's talk a little bit about some
testing pieces here
now a big question you might have is
well okay so i learned a ton of stuff we
learned about maintenance forking i
could do stuff on ganache i can use
brownies ganache i can use brownies main
net fork there's
i can do a test there's all these places
to do stuff where do i need to run my
tests the default for every single one
of your contracts is as follows you
always 100
need to have tests that pass on a local
brownie spun up ganache instance that
should be priority number one to get all
your tests to pass on this this means
that you will need to deploy mocks after
that the other place you absolutely need
to have tests or do some type of
development is on a test knob these are
going to be what's known as your
integration test and we'll talk more
about those later so those are the two
places you always need to have tests
development and a test net
i think testing on main net fork and
your own local ganache are optional
testing on mainnet fork can be done and
probably should be done whenever all of
your contracts and all of your
interactions are going to be on chain on
one chain without any external off-chain
components testing on your own local
ganache is really more meant for
tinkering and kind of exploring and
seeing things yourself so that's going
to be the setup here so great now let's
move into our most challenging example
once you pass and once you complete this
example you basically will have all the
tools to be an incredibly powerful smart
contract developer then after that we're
going to show you the chain link mix
package and how to do what's called a
brownie bake to automatically open up
this package with all these scripts and
all these contracts pre-built in this is
going to make our lives substantially
easier and faster for deploying our
smart contracts however let's go through
the process of understanding all the
pieces that are going to be inside of
this brownie mix
are you ready you should be let's get
excited and jump in
okay so let's get into our most advanced
smart contract project that we've made
so far this is going to be the best
example of a full scale application and
by full scale i really mean end-to-end
full suite of our brownie all of our
smart contracts are really solid here
what we're going to want to do is create
a lottery application where anybody can
enter the lottery and a random winner is
selected so let's get to it and let's
get started so first of course
we're going to make new directory
we'll call it smart contract lottery
cd and a smart contract lottery and then
open that folder
great we are now in our lottery
application
so let's go ahead and start a new
project
brownie init we've got our project here
now let's create a quick readme.md
to explain what we're going to be trying
to do here so number one we're gonna say
users can enter the lottery with f
based on a usd fee
so for example let's set the price to be
like fifty dollars and the users
actually pay with ethereum so we're
gonna have to get that conversion rate
number two an admin
will choose
when the lottery is over and then three
lottery will select
a random winner now something important
to note here
is since we have an admin here this
means that our application isn't
necessarily going to be truly
decentralized because we have a single
person chooses when the lottery is over
we could scale this out to have maybe a
dow being the admin or something like
that
or we could have the lottery
automatically open and close based off
some time parameters but for the moment
this is the setup that we're going to
have keep in mind even though this is
much less decentralized it's still going
to be a great use of smart contract
technology so first thing that we're
going to get started with of course is
our lottery contract so create a new
file
called lottery
dot sol and let's begin with our initial
setup here so let's choose our version
pragma
solidity
carrot 0.6.6
and this will be the version that we
want to work with here
we'll do contract
lottery
bracket here now let's think for a
second on what some of the functions
that are going to be what our main
functions are going to be here we'll
probably have a function enter
that'll be public
we'll probably have a function
get
entrance fee
to get the entrance fee of the
lottery we'll probably have a function
start lottery that only the admin can
call this will be public as well which
means we'll also probably have an end
lottery function
and those are really going to be the
main functions
the user can enter
based off the entrance fee we can start
the lottery and then of course we can
end the lottery so let's get started
with this enter function just because
this is most likely going to be the
entry point as we know since we're going
to want them to pay
using this entry function in ethereum
we're going to need to make this
function payable
and in here we're going to need to keep
track of all the different players
everybody who signs up for this lottery
to keep track of all the players we're
going to make
an address
payable
array
we'll make it public call players
and anytime somebody enters we'll just
do player
dot push
message dot sender
however right now we're not checking to
see how much value that they're actually
sending we want to set the price of this
to be at least 50
so we'll say 50 minimum so here we're
gonna have to do a require statement
requiring them to do at least 50
in order to do that we're probably going
to need to have some function to get the
entrance fee to check whether or not how
much they're sending is actually 50
so let's go ahead and make that get
entrance fee function now since we're
just going to be returning a number for
get entrance fee we can probably go
ahead and make this a public view and
have this return
a u and 256.
to get this entrancy we're first going
to have to have stored somewhere what
the entrance fee is we're going to store
this 50 minimum somewhere this is
something we'd probably want to set
right when our contract is deployed so
where can we put stuff like that
well in our constructor we'll do
constructor
public
we'll create a new variable
outside here we'll call it un256
public usd entry fee
in our constructor we'll set usd entry
fee equals
50. now because i like to have units of
measure always in way we'll also do
times
10
raised to the 18th
now we have some usd entry fee let's go
ahead and get this entrance fee as we
know since we're going to try to get a
conversion rate here we're going to want
to use a chain link price feed
so
we can head on over to docs.chain.link
we'll scroll down to get the latest
price
and we can even just go ahead and copy
paste this again
but for the sake of robustness let's
just walk through again how to actually
set this up we're going to need to pull
from the price feed to convert fifty
dollars to fifty dollars in each
so let's go ahead and create an agra
gator v3 interface
internal
f usd
price feed
and in our constructor
we'll go ahead and set this we'll say
fusd price feed
equals
ag redgate tor v3 interface
and we're going to want to grab an
address
from our contract addresses but of
course as you know as we've learned from
last time we're going to want to
parameterize this so we're going to want
to pass the address of our price feed as
a constructor parameter
so we'll do address
price
feed
address
and we'll have our aggregator v3
interface
we passed that price feed address then
of course since we're using an
aggregator v3 interface we're gonna have
to import this
from chain link
so we can just go ahead and copy this
from the documentation
and paste it right at the top
or if you want to rewrite it out
yourself feel free to do so
and of course since we're doing this
import here
new file
browning config.
we're going to want to add this as a
dependency so we'll do d
pendancies
smart contract kit
chain link
browning contracts
and we'll do add 1.1.1 again
and then compiler
sulk
remappings
we'll say at chain link
equals
this right here
we'll pull up our terminal
and we'll try this out do brownie
compile see if we're doing everything
right we forgot an spdx license
identifier
which is just a warning but let's add it
in anyways
spdx
license
identifier
mit i should probably spell me
remappings right
mappings
and let's try to compile again
all right lovely so we at least know
that
we are compiling correctly here awesome
so now that we have a price feed let's
go ahead and set up this entrance fee so
we're of course going to need to get a
price from this price feed so we can
even check the documentation how to do
that
we can call this latest round data
function
so we could copy paste it i'm just going
to go ahead and rewrite it but again we
don't need round id started at timestamp
or answered in round we only need price
so we can go ahead and ignore these
variables on our call
so what we'll do is we'll do blank comma
into price
and then
comma comma comma
equals
fusd price feed dot latest
round data
and this means we're just going to get
the price here now we're going to want
to do a little bit of quick math
typically if we're setting the price at
50
and we have
a price feed of two thousand dollars per
eth
we would just wanna do
fifty divided by two thousand
but of course since solidity doesn't
work with decimals we can't actually
just do this
so we'll have to do
50
times
some big number divided by the 2000 so
we're going to go ahead and do it like
that but first let's go ahead and
convert this price from into 256 to uint
256.
so we'll say
you went 256
adjusted price
equals
you went 256.
you in 256 price
and then
since we know
we're going to be using an ethereum usd
price feed that has eight decimals
let's also just convert it to having 18
decimals as well
so we can also do times 10
raised to the 10th
so now we can have 18
decimals
now that we have this adjusted price
we'll do um 256
cost to enter
it's going to equal
usd
entry fee
times
again we're going to want to times it by
some big number here so we'll just times
it by 10 raised to the 18th
this way usd entry fee
has 18 decimals but it has an additional
18 decimals here that'll be canceled out
with our price feeds and the math will
work divided by price
and then we'll return
cost to enter
now of course since we're doing some
interesting math here it's recommended
to use safe math and use safe math
functions we're going to skip over the
safe map functions here again because in
the newer versions of solidity you don't
really have to use them but i think it's
important to note here that sending this
code this exact code to production would
be a bad idea for at least the reason of
the safe math functions but in any case
we have a function here we think our
math is pretty good but i know for a
fact that my math is usually not very
good so let's go ahead and do some
testing as we code just to make sure our
get entrancy function is working
properly so based off of our last lesson
let's talk about
how do we want to test
this
well we could do a main net fork here
because we're only working with some
on-chain contracts and some math we will
at some point have to do our develop
mint
with marks
and of course our test net
i kind of want to just do a quick and
dirty way so let's try our maintenance
fork just for now just to see if
if this is really making any sense if
the current price of ethereum is 2 500
or this much here
and we want the price of this to be
fifty dollars we do 50 divided by this
and we get
.019 so this should be approximately
what we get for our eat value so if we
were to write a test
test
lottery dot pi
if we were to test this function we
would expect to get 0.019
or in way it'll be 1 9
1 2 3 4 5 six seven eight nine ten one
two three four five six
we expect to get approximately this so
let's go ahead and create a function
that tests us so we'll do test get
entrance fee
and here we'll deploy lottery
and in here the first thing we need to
do is deploy this lottery function of
course so we'll do from
brownie
import
lottery
in order to deploy this we're going to
need to get an account
we are going to import our helpful
scripts from the last project to this
one too so we can get our get accounts
but for the time being
we can actually just use accounts 0 from
brownie so we'll say count zero
let's start with def then we'll do
lottery equals
lottery dot deploy
from
account
and ah of course we have a parameter
here of our price feed address
so we're gonna have to add
some type of parameter here for now
let's just hard code it from our config
and we'll go into our config and we'll
start our networks flag
we're going to be working like i said on
the maintenance fork for this quick and
dirty here
we'll call f
usd price feed
grab the fusd price feed
from mainnet since we're going to be
doing a main net fork here
pop that in here
now we can just say
from config
networks
network dot show active
usd
price feed
of course we're going to need to import
network here
and now we can do our kind of quick and
dirty test we can do lottery
dot
get entrance fee
am i spelling that right get entrance
fee
yes
assert
lottery.get entrance fee should be
greater than
let's just say let's just go down 18
or if we wanted to make sure we're
actually doing this right we'll do from
three import
web three
we'll do web3.2 way
0.019
comma ether
should be greater than
and then we'll
even do
0.018 just to make sure
and it should be less than
0.01
now these numbers are of course going to
be a little bit different for you
and if you want you can go ahead and
skip this part so that you don't have to
do the math but it is kind of nice to do
a quick sanity check saying okay like
based off what things are right now what
would this price end up to be now in our
last section we made a mainnet fork dev
network
i'm going to just go ahead and customize
our mainnet fork the way that we showed
you guys how to do maintenance fork dev
this way you can use accounts and we can
be a little bit more robust here
to do this we're first going to have to
delete brownie's internal built-in
mainnet fork
so we'll do brownie
networks
delete
mainnet fork
maintenance fork has been deleted
and now let's go ahead and add our own
maintenance fork using alchemy
as our ethereum connection
so you'll want to create a new app i've
already created one here called smart
contract lottery
we'll view the key
and this is the http endpoint that we'll
use
so to do this we'll do brownie
networks
add this will be a development chain
we'll call this
maintenant fork
it'll be a ganache cli
the host is going to be our local host
so 127.0.0.1
and the fork is going to be equal to
our alchemy http here
we'll do accounts equal 10 that way we
can use the accounts
do the new monarch
equals brownie
import is going to be eight five four
five
and great maintenance fork has been
added now that we have this here we can
go ahead and run our test
brownie
test dash dash network
mainnet fork
whoops looks like we got a little
compile error on our math here
oops it looks like we're divided by
price when we need to be divided by
adjusted price and we forgot the
parentheses on latest round data
let's try this again
and i put an extra comment in here
let's try this one more time
lovely and it looks like we're forking
correctly
and awesome it looks like our test
indeed passes here
of course we know that we're going to
want to change this because this isn't a
great way to actually test our contracts
here but it can be a nice sanity check
and we know we're going to have to
refactor this as well
for mocks and for accounts
but we'll get to that in a little bit
awesome sanity check complete let's get
back to our contract here
so we are getting the cost to enter
correctly perfect we're getting this
entrance fee what that means we can do
in our enter function we can do require
message.value
it's got to be greater than or equal to
our get entrance fee function
and if it's not
give them an error of not
enough
eath
we have a way for them to enter and we
have a way to get the entrance fee but
we want to make sure that we're not
ending the lottery before the lottery
even starts right or we're not entering
a lottery when a lottery hasn't even
begun so we're going to want a way to
iterate through the different phases of
this lottery and we can do that with
what's called an enum or an enum
according to the solidity documentation
enums are another way to create
user-defined types in solidity
we saw an earlier version of doing this
with a struct enums are a little bit
different in that they're explicitly
convertible to and from all integer
types so what does that actually mean
well
we can have an enum
like this action choices go left go
right go straight and sit still they're
just more readable ways to say
go left is going to be represented as
state 0 go right it's going to be state
1 go straight state 2 sit still state 3.
so for our lottery contract we're going
to want to create
this new type that represents the
lottery state so to do this we'll do
enum
lottery state open
closed
and calculating winner
this means that we have a new type
called lottery state with three
positions open closed and calculating
winner these different states are
actually represented by numbers so open
is actually a zero
closed is actually one and calculating
winner is actually a two now that we
have this new type we can create a
variable of type lottery state so we'll
say
lottery state
public
lottery state
and right when we initialize our
contract here we're going to want to set
our lottery state to being closed
so in our constructor we'll do lottery
state
equals
lottery state
dot closed
now since these are represented by
numbers as well we could also just do
lottery state equals
1
because 1 stands for closed however it's
much more readable to do
lotterystate.closed
now that we have a lottery state
in our enter function we can require
that the lottery state
is going to be
equal to
lottery state
dot open
so we can only enter if somebody's
started this lottery and that's exactly
what we're going to do in our start
lottery function
we're going to do a require in here
that the lottery state
is going to be equal to
lottery state dot closed
we can even add
a failure function here
saying
can't start
a new
lottery yet
and when we do start this lottery we'll
say lottery
state
equals
lottery state dot open
now when somebody starts the lottery
they'll be able to
enter of course this
start lottery bid here needs to be
called only by our admin so this is
where our
only owner modifier is once again going
to come into place we could write our
own only owner modifier or we can once
again use open zeppelin's access control
and open zeppelin's ownable function
instead which is what i'm going to use
here so we're going to go ahead and grab
this
copy this
paste it in
import at open zeppelin contracts slash
access ownable
and of course since we're doing this
we're gonna have to add this dependency
into our config
we're gonna be using
open
zeppelin
open
zeppelin
contracts at 3.4.0
we're going to remap
at
open
zeppelin equals
this
oops
and then we'll say our lottery is
ownable
perfect
now we'll try to compile this
awesome looks like brownie grabbed
everything correctly and we're good to
go great
now we can finally move into our end
lottery function
this is where we're actually going to
choose a random winner here
we only want the admin to be the one to
actually end the lottery so let's add
the only owner modifier here
and let's talk a little bit about
randomness because this is what we're
looking to do now we're looking to get a
random winner here now as you know the
blockchain is a deterministic system
right and this is super ambitious
because that allows us to do all these
smart contracts and have this system
that can actually reach consensus very
easily random numbers are much harder if
let's say you had a blockchain with a
whole bunch of different nodes and each
node responds and gives their own random
value well each node is never going to
be able to sync up and say hey you know
we all agree on a random number what you
could do is you could base the random
number on some other attributes in the
system
but then it's not really random it's
actually going to be pseudorandom so
getting truly random numbers in a
deterministic system is actually
impossible and if you know a lot about
computer science you actually know that
even when you call like math.random in
your javascript what your computer is
really doing is it's looking at some
place in memory grabbing some value and
saying hey this is probably random
enough here go ahead and use this now in
smart contracts especially when working
with any type of financial application
such as a lottery having an exploitable
randomness function means that your
lottery is at risk of being hacked or
destroyed and this isn't even a fairy
tale at the time of recording about two
weeks ago i did a rundown on an exploit
where a protocol used insecure
randomness and got hacked for seven
hundred thousand dollars so i am going
to show you this insecure way first and
the reason that i'm going to show you is
that it is a quick and dirty way to get
a pseudo random number but please do not
use this in any production use cases i'm
going to show you a method that's often
used to teach people how to get random
numbers and then we're going to explain
why it's so vulnerable and not a good
method of randomness and what some
insecure protocols will do is they'll
use a globally available variable and
hash it so in your smart contracts
there's actually a number of globally
available variables one of those as we
saw above
is going to be message.value right it's
going to be the value that's sent with
the transaction another globally
available variable is going to be
message.sender
you can actually see a whole list of
these different globally available
variables in the solidity documentation
here so since there are these globally
available variables a lot of times some
will see something like block.difficulty
which returns the current block
difficulty
now one of these globally available now
one of these globally available
variables is going to be block
difficulty or block dot difficulty it's
the current block difficulty remember
how i said that the time between
different block generation is called the
block time
well you can always keep that block time
as is by changing the block difficulty
over time the harder the problem or the
harder the proof of work algorithm
the longer it's going to take or the
more nodes you're going to need to solve
that problem there's this constantly
recalculating metric called ethereum
difficulty or block difficulty depending
on the chain that you're working on that
constantly changes
so you might think this would be a great
use of randomness right because it's a
somewhat hard to predict number so what
a lot of people do is they think that
hey those sound pretty random let's use
them as a unit of randomness and what
you'll see is you'll see like something
like uint
256 which is
again this hashing algorithm
let's do something like abi dot encode
pact
so i know there's a whole lot going into
this line and let's talk about it
so first as we can see
is that we're casting or we're
converting everything in here to being a
uni-256 the reason that we're doing this
of course is because we're going to want
to pick
a random winner based off of an index
right we're going to want to pick
somebody some random winner in our
players array or our players list
so we say okay whatever number that
we're going to use that's going to be
the index of the winner that we're going
to randomly pick
then they use cache 256 which is again
our hashing algorithm so they hash a
whole bunch of variables together
and they do this abi dot encode packed
api is another keyword
for some low-level work
and they'll add maybe a nunsen they'll
add the message on sender
block that difficulty and block the
timestamp basically what they're trying
to do here is take a bunch of seemingly
random numbers
mash them all together in a hashing
function and then say yeah this this is
pretty random but the issue here is that
the hashing function itself isn't random
the hashing function is always going to
be exactly the same could check 256 it's
always going to hash everything exactly
the same way so we're not actually
making it more random by hashing it all
these numbers inside are the pieces that
actually determine how random it is so
if the block to difficulty is random
then this will be a random method if the
blocked out difficulty isn't random then
this won't be a random method and the
blocked difficulty is not random
difficulty
can actually
be manipulated by the miners
in time stamp
timestamp is predictable
nuns is predictable
aka
transaction number because in this
regard they're using the nuns as some
transaction number
and message.sender
is predictable
when using a random number in this way
the hashing algorithm is always going to
be the same union 256 is always going to
be the same we have a predictable number
a predictable address
a predictable timestamp
and then a manipulatable value
so all this is really doing is giving
the miners the ability to win the
lottery or win whatever lottery that
you're working on
so this isn't going to be an effective
way to get a random number this is an
unacceptable way to get a random number
in our applications yes we do have this
only owner modifier here which means
that we are the ones who are going to
choose when to call this so it is still
centralized in that regard
but let's just teach you the best
practices for working with random
numbers right from the get-go so you
don't run into any issues
i'll explain what this part is doing in
a little bit in order to get a true
random number we are going to have to
look outside the blockchain the
blockchain itself like i said is a
deterministic system so we need a number
outside the blockchain but what we can't
do is we can't use just an api that
gives a random number right if that api
becomes corrupted if they're malicious
if they go down if something happens
etcetera what we need is a provable way
to get a random number and chain-link
vrf is actually that solution chain-link
vrf it stands for chain-link verifiably
randomized function and it's a way to
get a provably random number into your
smart contract it has an on-chain
contract that checks the response of a
chain-link node to make sure the number
is truly random using some cryptography
magic it's able to check a number of the
parameters that the chainlink vrf
started and ended with to make sure that
it's truly random it's already used for
protocols like avagochi
ethercards pool together and a whole
bunch of other protocols as well because
it is a secure reliable truly provable
way to get a random number which is
incredibly powerful in a decentralized
system so that's how we're actually
going to get our random number here so
let's work on getting that
what we can do is we can go ahead and
head right over to the chain link
documentation to actually learn how to
work with one of these let's go over the
chain link documentation just to make
sure that we get it right so if we go to
the get a random number here
we have all the documentation you could
ever want so if you ever get lost or
confused you can always come right back
here to work with it what we're going to
do is we're going to deploy their simple
version in remix version of working with
the chainleaf vrf and we're going to
walk through a minimalistic contract to
see how it actually works in a contract
so once again we hit this remix button
remix pops up and we immediately get
this random number consumer.soul
in our files that we can check out so
awesome so here is our files right here
we can see that this is actually using a
different chain than what we've been
using we've been mostly working with
rink b
but for this demo it's actually on coven
so we can do some work with kovin here
and remember if you do want to stay with
rink b you can always go to this
contract addresses section of the vrf
and grab these addresses to use so
what's going on in this contract how do
we actually use this well as you can see
the first thing that happens is we're
importing some code from the chain link
package and our contract is inheriting
the abilities of this vrf consumer base
contract so we're going to see what
functions we're actually going to use
that are inherited from this contract
and the first thing that we notice is we
can see that our constructor in here
does some weird stuff
it looks like it almost has two
constructors
so what's actually going on here well
let's look at this vrf consumer
base.cell contract in the chain link
github
so we can come to the chain link github
here
we'll go to evm contracts or depending
on when you're watching in this it's
migrating to contracts at some point
we go to evm contracts we'll go to src
so once we're using v0.6 we'll go there
and we'll look at this vrf
consumerbase.sol
as we can see this vrf consumer base
that we're importing has its own
constructor and it takes an address for
the vrf coordinator this is the on chain
contract that actually checks to make
sure our numbers are random and the
address of the chain link token which
we'll talk about erc20s in a little bit
what we're doing is we're also
inheriting the constructor into our
contract
so this is our constructor for our
random number consumer but we can also
use the constructor of the vrf consumer
base
and this is actually how we go ahead and
do that we grab the constructor of the
vrf consumer base and pop it in here
now it's taking two addresses it's
taking the vrf coordinator
and the link token like i said the vrf
coordinator is a contract that's been
deployed on chain that's going to verify
that the return of the chain link node
is truly random and we're going to use
the link token as a payment to the chain
link node for its services and then we
also have a key hash and a fee defined
inside of this constructor as well the
key hash uniquely identifies the chain
link node that we're going to use and
then the fee is how much link we're
actually going to pay to the chain link
node for delivering us this random
number now let's talk about a couple
things here
in ethereum whenever you make a
transaction you have to
pay some eath gas
right or transaction gas
this is to pay the smart contract
platform a little bit of eth for
performing our transaction with a smart
contract with a smart contract that
operates with an oracle we have to pay
some link gas or oracle gas
this is to pay the oracles a fee for
their services for providing data or
doing some type of external computation
for a smart contract the question that
might then follow up is oh okay well how
come i didn't have to pay
when we did this price feeds thing
well for price feeds
somebody had actually already paid
for the data to be returned and if we go
to data.chain.link and we scroll down we
can actually see a list of sponsors here
that are paying to get this data
delivered so they're already paying the
oracle gas to bring this data on chain
for us since no other protocol is
getting a random number for us we're
actually going to have to pay the oracle
gas here now in this contract we have a
function called get random number which
is going to return a bytes 32
and what it's going to do it's going to
call this request randomness function
which is inherited from this vrf
consumer base if we look in here
we look for request
request randomness we can see there's a
function right here
called request randomness this function
is going to send our oracle fee or the
link token
and it's going to call this
specific to the link token function
called transfer and call
this function is going to call a chain
link node now i'm not going to talk now
i'm not going to go into exactly how
it's doing that right now but we will
talk about it in a little bit so we call
this request randomness function
and we send the key hash and the fee
remember the key hash uniquely
identifies the chain link node
and the fee is going to be how much
oracle gas we're going to pay if you
ever get lost on how much to pay or what
the contract addresses are you can
always head over to this vrf contract
section and see where the most recently
deployed
vrfs are how much the fee is etcetera
now here's where it gets a little bit
interesting
getting a random number actually follows
what's called the request and receive
style of working with data let's go
ahead and just try this out and i'll
explain what this means once we see it
now we're going to save the answer to
this random result variable here and
let's just go ahead and try this and see
what happens
so we're going to switch to our injected
web 3 and since we're now swapping to a
new test network this means that we have
to get tested eth and test that link
again
we can always look for the link token
contracts page to find the most
up-to-date faucets so we'll scroll down
we'll find coven
looks like this is the at link faucet
and the test and eat faucet
so here's our kovin faucet we'll just
want to switch from rink b to coven
grab our address
paste it in
send me a hundred test link
here's our transaction
we can see we're transferring
some erc20
we'll take this contract address we'll
add it to our metamask by copying the
address
scrolling down to add token
pasting it in here i already have the
address in here so i'm just going to go
ahead and hit cancel for now
and we'll also want some testnet coven
ethereum which looks like this faucet
has it
so we'll paste the address in here
i'm not a robot and we'll do send me 0.1
test eth and perfect now that we have
some tests on ethereum
and some test that link we can proceed
we're going to make sure we're on the
coven test network
and we're going to deploy
our random number consumer gist here
let's go ahead and hit deploy
metamask pops up we're going to go ahead
and confirm
i didn't explain this fulfill randomness
function intentionally you'll see why in
a second
and great a random number consumer comes
up
let's check what our random result is
right now it's obviously zero because we
haven't got a random number so i'm going
to do something intentionally wrong
because there's a good chance that
you'll run into this at some point
if i hit get random number right now we
see this air gas estimation failed
we have plenty of eath why would this
fail the reason that it's failing is
because the contract doesn't have any
oracle gas so we got that gas estimation
failed because we need to fund this
contract address with some link to
actually get a random number so we're
going to hit this copy button and this
is going to copy the address
and we're going to come into our meta
mask here
and we're going to send
this address we're going to paste it
there
swap to link and we'll send it one link
this is probably overkill
because as you saw
the fee is only 0.1
but we're just going to be overkill for
now
and great now that this contract has
some test net link now we can call this
get random number button because we can
actually pay the chain link node to
actually return our random number so
we're going to go ahead and do confirm
and this is fantastic so we're paying a
little bit of transaction gas to make
this transaction to make this request
and then we're paying a little bit of
oracle gas to make this transaction now
so the transaction
now so the transaction confirmed but if
i hit random result now it's still going
to be zero
so why is that what's going on well
getting a random number like this
actually follows what's known as the
request and receive cycle of getting
data you can read more about it here in
this basic request model in the
documentation so in one transaction we
actually request some data or in this
case a random number and then in a
second transaction the chain link node
itself
will make a function call and return the
data back to the smart contract in this
case the function that we're calling is
fulfill randomness it calls this fulfill
randomness
with byte32 request id which is going to
be the request number of when we call
this
and it's going to return with this
random number called randomness
so after we wait a little bit
if we hit random result now we can see
indeed our random number is in here
again the reason that it's in here is
because we actually had two transaction
occur
one paid by us
when we called get random number and one
paid by the chain link node when it
called fulfill randomness now i lied to
you a little bit technically that vrf
coordinator contract calls this function
and then the chain link node calls the
vrf coordinator function but for
simplicity's sake you can kind of just
think of it as the chain link node
itself is calling this fulfill
randomness function so now that we know
how to do this from remix let's go ahead
and add this to our brownie project
so actually before we even do that we
need to require so before we even get a
random number let's change the state of
our lottery so now we'll do lottery
state
equals
lottery state
dot calculating winner
and while this is happening no other
functions can be called right this will
lock out
nobody can start a lottery and nobody
can enter a lottery while we're
calculating the winner
awesome so now that we know a little bit
more about random numbers and everything
that we're doing here let's go ahead and
try implementing this now
so in our chain link smart contract docs
of course we're going to scroll down
we're going to go to our get a random
number bit here
we can copy and paste all this code as
well
into our smart contracts so the first
thing that we're going to need to do of
course is
import the vrf consumer base code
let's move back over
scroll to the top and we'll just paste
this in at chain link slash contracts
src
v0.6 vrf consumer base and we'll inherit
this into our lottery contract so we'll
say the lottery is vrf
consumer base
and it's ownable let's take a look at
this vrf consumer base in the chainlink
github here
if we scroll down
to the constructor of our vrf consumer
base we can see it takes these two
parameters the address of the vrf
coordinator and the address of the chain
link token
we can use a constructor we can use a
constructor of a contract inherited in
our contract inside our constructor
so what we'll want to do is we want to
come down to our constructor and right
after this public keyword we can add any
additional constructors from inherited
smart contracts
so we'll say constructor and this is our
normal constructor and then we'll put
vrf
consumer base
and we'll add the vrf consumer base
addresses in here
we know that it's going to be a vrf
coordinator address and a link token
address
similar to the price feed these two
addresses are going to change based on
the blockchain that we're on
so it'll probably make sense for us to
parameterize them the same way we
parameterize the price feed address
so in our top level
constructor parameters we'll add
an address
for the vrf
coordinator
and we'll pass this to the constructor
of our vrf consumer base
then we'll also grab an address for the
link token so we'll do address
link
and we'll pass this
to the vrf consumer based constructor as
well
great what else do we need to make this
work well back in the documentation we
can see we need a fee
and a key hash the fee is associated
with the link token needed to pay for
this request
so we'll make a public variable
uint 256
public
fee since this might change blockchain
to blockchain we'll have this as an
input parameter as well
so we'll do uni-256
underscore fee
and in our constructor
we'll do fee
equals underscore fee
we'll set our global variable
to fee
and i need a comma here and no semicolon
here what else do we need
well we need a key hash
the key hash is a way to uniquely
identify the chain link vrf node
so create another one we'll do
bytes 32 public key hash
we'll add this as a parameter in here
bytes32
keyhash
and then we'll say
keyhash equals
underscore keyhash
perfect our contract is coming along
great here
now that we have the main pieces that we
need how do we then request this random
number
well if we scroll down in the
documentation
we can see we have this request
randomness function that we need to call
if we scroll back to our vrf
consumer-based contract this request
randomness function is a built-in
function from the vr of consumer base so
our contract can natively call this
request randomness function right in our
contract and you can see it takes a key
hash and a fee as its parameters
so right in our end lottery function
we can add this function and we can see
this also returns a bytes32 called
request id this return syntax is pretty
powerful
you can actually identify the name of
the variable you want to return right in
your write in your function declaration
so by saying bytes32 request id we're
saying we're going to return a bytes32
variable named request id so right in
our function here
we can do request
randomness
because again that's this function that
we're importing
passing it the key hash
and the fee
this will return
a bytes 32 called request id
so this is actually doing this
and having our function
having our function declaration tell us
that there's going to be a variable name
request id
is going to be exactly the same as if we
did bytes 32
request id equals request randomness now
this function call follows again what
we've talked about as the request and
receive mentality the request and
receive architecture
this means that in this first
transaction we're going to request the
data from the chain link oracle in a
second callback
transaction the chain link node is going
to return
the data to this contract
into another function called fulfill
randomness so again if we look back in
our vrf consumer base we can see it has
this function raw fulfill randomness we
can read some of the comments in here
saying raw fulfill randomness is called
by a vrf coordinator when it receives a
valid vrf proof raw fulfill randomness
will then call fulfill randomness so
there's a little bit of contract tag
going on but it's going to eventually
call this fulfill randomness function
which is going to be what we define in
here
and that's how our contract is going to
know what to do once it gets the random
number back so in our first transaction
we're going to end the lottery request a
random number
and then a second transaction later on
once the chain link node has created a
provably random number it's going to
call a second transaction itself
based off of what we define
we just have to call it
fulfill
randomness
and as you can see it takes a byte 32
request id and a random number so
in here we'll do fulfill randomness it
takes a byte 32
request id
and then a uin256
randomness
we don't want anyone else to be able to
call this function we only want our
chain link node to call this function so
we can return a truly random number
so we're going to make this an internal
function
it's internal because actually the
chain-link node is calling the vrf
coordinator
and then the vrf coordinator is calling
our fulfill randomness
so we'll make this internal so that only
the vrf coordinator can be the one to
call and return this function
and then we're going to give it a
keyword of override this override
keyword means that we're overriding the
original declaration of the fulfill
randomness function our vrf consumer
base has a function fulfill randomness
defined but it doesn't have any
parameters or anything about this
function actually laid out this function
is meant to be overridden by us and
that's exactly what we're doing right
here so in this fulfill randomness
function let's go ahead and define
what's going to happen once we get this
random number back so before we can
process this random number let's just
check to make sure we're even in the
right state so we'll do require
our lottery state is going to be equal
to
lottery state dot
calculating winner
and if we're not in that state
we'll just say
you
aren't there yet
my auto format is is on for this one so
it's uh it's jumping in then let's just
do another check to make sure we
actually get a response so we'll do
require
underscore randomness
is greater than
zero
and if it's not we'll just say random
not found
now we need to pick a random winner
well we need to pick a random winner
specifically
out of our list of players our list of
payable public players so our players
array is just a list of players so it's
like one player one player two player
three player four
and they're each at a different index
what we can do then to pick a random
winner is to do what's called a modulo
function in fact let's even open remix
to do an example of this remix let's pop
open a new contract we'll call it
mod.sol
do pragma
solidity
carrot 0.6.6
we'll do contract
mod
and in here we'll do a constructor
blank constructor
and we'll get a global variable you went
256
number and we'll set it equal to 5. and
we'll go down to 0.6.6
save compile
and you know let's even just get rid of
the constructor
let's now create a function
called do mod
we'll take a un256
mod value
make this a public function
public
view returns
ui 256
and we'll just return
5
modulo
mod value
now let's go to javascript vm we'll
deploy this
we'll go in here
so our number is right now five and
let's learn about how the modulo works
if we have this do mod function
what we're doing
is
the module divides
by
the number
and returns the remainder
for example if we did 5 mod 5 what do
you think we're going to get
so we're going to do 5 divided by 5 and
then return the remainder
well 5 divided by five is one and
there's no remainder there's no decimal
there so five mod five should be what
zero exactly well what's five mod four
then
well four can go into five evenly once
but there's one number left over so five
mod four is going to be
one
five mod three is going to be two five
mod one is going to be zero right since
one goes with everything this is how the
mod function works and it's this little
percent here we can use that mod
function
in our fulfill randomness
with the length of our players so we can
say uint 256
index of winner
is going gonna be equal to
the random number that we got
modded
by the players dot length so let's say
for example we had seven players
sign up and our random number was 22
well we want to get one of these random
seven players so
we would do 22
mod 7.
7 divides evenly into 22 three times
with one left over seven
times 3
equals
21.
difference between 21 and 22
is 1
7 times
4
is 28 so we know this is how we know
we've reached our upper limit so this is
how we can get a random number
based off of the index
now that we have this index what we can
do
is we can say the winner
equals
players
of the index of winner
and just to keep track let's make a new
variable called recent winner at the top
we'll do address
public
recent winner
we'll grab this recent winner instead of
winner we'll say recent winner equals
players and this index of winner here
now that we've got a winner wallet we
want to pay them all the money
gathered from our enters here
so what we can do
is we'll do
this recent winner
dot transfer
the entire balance of this address
so we'll say address of this
that balance
and perfect
we'll transfer them everything that we
have
then of course
we're going to want to reset the lottery
so that we can start from scratch we can
start blank again
so we'll do players
equals new
address payable
array of size 0.
so
we're just resetting players to just be
a brand new array then we're going to
change our lottery state
to being
lotterystate.closed
because the lottery is now complete and
i often also like to keep track of the
most recent random number
so at the top
i'll do a uint 256 public
randomness
variable
and in our fulfill randomness i'll say
randomness now equals
underscore randomness
and perfect we now have a contract here
of course we haven't actually tried it
out but we're assuming that it works
great so you know what this means it's
time to go into testing mode testing and
development mode but let's even just try
to do a brownie
compile first
looks like we have
an issue here
send and transfer are only available for
objects of type address payable
not address oops looks like we made our
recent winner just an address but it
needs to be an address
payable
so let's try browning compile again
and beautiful we at least know it's
compiling so that's a great sign let's
now move into our testing and
development phase as you are starting to
figure out we can ignore these file
import callback not supported bugs and
vs code for now i'm sure the solidity
linter will get better as time
progresses but great so now let's go
ahead and move into actually testing and
working with everything here
so let's go ahead into our scripts
and we'll make a little deploy script
first
let's do a new file
call it deploy lottery that pi
and let's go ahead and deploy our
lottery
so same as always we'll do def main
we'll come with a new function called
deploy
lottery
and then we'll do def
deploy
lottery
and then we'll just have a pass for now
and if we run this
brownie run scripts
deploy lottery.pi
our default network is not defined which
means the default is going to be
development
and we can even
verbose here develop
meant write that in our brownie config
run this
gnosh will get spun up
and nothing will happen because our
deploy lottery function doesn't do
anything right now
awesome the first thing we need always
to deploy a contract is we need an
account
so we'll do account
equals and we've been using this
getcount function for some time that
we've been adding in a helpful script
section so that can pull from a real
test net or from a local development
environment if we like so to do this of
course let's create our new
helpful scripts
dot
pi we'll create our underscore
underscore init underscore underscore
dot pi
so that python recognizes it as a
package
and in here we'll create a new function
f get
account
for now we'll just have it pass
we'll copy this
into our deploy lottery we'll do from
scripts.helpful
scripts
import get account
now this
now this
is what our get account looked like
in our last project
along with that we had
these forked local environments
we also had from
brownie imports accounts
and network and config
to make this look really nice right
let's flush this out just a little bit
more so it's even more robust
right now as we know
we have a way to use
brownies ganache accounts
and we have a way
to use
our environment variables
however there was a third method that we
learned that isn't identified here
accounts.load
and this is with our id
if you still have your account and you
still have all your brownies set up if
we do brownie
accounts
list
you'll see we have a couple accounts
here
we want our get account to be
even more liberal so that if we wanted
to use one of these as well we could so
let's modify our get account script here
a little bit let's first get rid of this
else
and rid of this indent
what this will do is this will be our
default
if nothing that we define prior to this
is defined we'll just default to grab
right from our config which since we are
doing that
let's create our dot env
we'll paste our different variables in
here our private key web 3 and fura and
etherscan token
and in our brownie config of course
we'll do wallets
from key
private key
and now let's flesh this out a little
bit let's add an index
and an id
index equals none
and id
this way if we pass an index to our get
account function we'll just use
an index from this accounts variable
if we pass an id
we'll have
trying to do this accounts.load here so
now let's change this up a little bit
we'll say if an index was passed
we'll just return
accounts
on that index
otherwise if we're doing a local
blockchain we'll just return account to
zero
but if there's an id
we'll return
accounts.load
id
whoops we need to actually move this up
a little bit
so that it's before
our local blockchain checking
so now in our deploy lottery
we could do something like get account
id equals
free code camp
oops and this is actually free code
account
precode camp account let's try one more
time
it's going to ask for our password here
now we have a much more liberal get
account function
so now that we have a count we can
actually deploy our lottery
so we'll say lottery
equals
lottery.deploy
and this is where we're going to import
from brownie
import our contract lottery
and we're gonna have to add in
all these different variables so if we
go back over to our lottery contract
we need to give it a price feed address
a vrf coordinator
a chain link token
a fee and a key hash
now the way we did that in fund me is
that we did it in a way where we checked
to see if we were on a local chain or
not if we weren't on a local chain then
we would just pull our addresses
directly from our config if we weren't
on a local chain though we'd deploy some
mocks and use the address of those mocks
we're going to want to do the same thing
here but let's make our lives a little
bit easier
we can take this whole process and put
it into its own function
so let's make this a little bit easier
mentally the first thing we're going to
need is this price feed address
if we're on a real test net of course we
would just go into our brownie config
and add the address which we will do
we'll add our rink b
network here in a little bit but for now
don't worry about that
but if we're not on a wrinky chain what
we're going to need to do is deploy our
mock
we're going to wrap
all of this mocking and checking into a
single function called
get contract
and we're going to add this function in
our helpful scripts
so let's create this function called get
contract
do def get contract
pass
let's talk a little bit about what we
want this function to do
let's add one two three
three double quotes here and three
double quotes here to start what's
called a doc string this will define
everything about this contract so we're
just going to say
this function
will
grab the contract addresses
from the brownie config
if defined
otherwise
it will deploy
a mock version
of that contract
and return
that mock contract
for the arguments of this chain
we're going to take a contract name
this is going to be a string
and it'll return
a contract
or in particular it's going to return a
brownie
dot network
dot contract dot project
contract
the most
deployed
version of this contract
so for example if we have a mock v3
aggregator contract
it'll do the most recently deployed
version of that with this -1 syntax
now this get contract function if this
is a little confusing to you
again we're going to go over this chain
link mix in a little bit and inside of
this it has a more robust
description of what's going on in this
get contract bit
so you can check that out if you want to
learn more but let's go ahead and
actually define this
so we obviously want a contract name
as an input parameter so let's go ahead
and add contract name in here
meaning that this getcontract function
we'll get something like f
usd
price feed
right
that's gonna be the same as what's
defined in our browning config and from
this name we're gonna get the type of
contract that it is
contract type
and to do that we're gonna have to
create some mapping that'll map the
contract names to their type
so right above we're gonna do contract
to mock
and we're to create a mapping in here
which will map everything out
so
an fusd price feed
is going to be of type
mock v3
aggregator
so
we have to import mock v3 aggregator
from rounding
so now we're saying anytime you see fusd
price feed you know that that's going to
be a mock v3 aggregator if we need to
deploy a mock
so we'll say contract type
is going to equal
contract to mock
of the contract name
now we need to check okay do we actually
even need to deploy a mock
so sure let's check if we're on a local
blockchain
so we'll say if
network.showactive
is in
our local blockchain environments
and we'll skip the forked local
environments because again
we don't need to deploy a mock price
feed address on a fourth local
environment
which say if network.showactive is in
the local blockchain environments
then we'll check
to see if one of these contracts has
already been deployed we'll say if the
length
of contract type
is less than or equal to zero
then we're going to go ahead and deploy
mox
so this is equivalent to doing
something like mach v3
aggregate or
length
we're checking how many mach v3
aggregators have actually been deployed
if none have been deployed we're going
to go ahead and deploy them so
we're gonna have to create this deploy
mox function so we'll do def deploy
mox
and this is gonna be the same as what we
did
in our brownie fund me right it's gonna
be the exact same
so we'll say
account equals
get account
i'm not going to put the prints in here
but you absolutely can we'll say mock
price feed
equals
mock v3 aggregator
[Music]
dot deploy
we'll need to give this some decimals
and an initial value so right above
we'll do
decimals
equals eight initial
value equals two thousand one
two thousand one two three four five six
seven eight
and in our deploy max we'll say decimals
equals
decimals
initial value equals initial value
to deploy decimals and
initial value
of course this is going to be from
account
and for now that's it i'll say print
deployed
all right great so now we have a way to
actually deploy the mock price feed here
so let's go back up to our get contract
function
so we have a way to deploy the mock
if one already isn't deployed
now what we're going to want to do is we
want to get that contract right we're
going to want to get that mock so we'll
say contract
equals
contract type
minus one
right so this is going to be equal to
doing
mock v3r gregator
minus one
this is saying hey let's grab the most
recent deployment of the mock v3
aggregator which is exactly what we want
perfect so this will work
perfectly
for our
development context however we're not
always going to just want to deploy to a
development network we're also going to
want to deploy to testnets
so then we'll say else and this is where
we'll just grab that contract from the
running config for example fusd price
feed so we'll say
contract address
equals config
networks
network.show active
and that contract name
for example again if it's fusd price
feed it'll be fused price feed here
and the way we're setting it up it's got
to be the same as what's in our contract
to mock dictionary here so up here the
way that we did it was we actually got
the contract because we had its contract
type
based off of browning for here we're
gonna have to interact with the contract
getting those two pieces that we always
need which are gonna be the address we
actually have the api from our mock v3
aggregator type right here and we just
got the address so we can create this
new contract type by saying contract
equals contract
dot from abi
and this contract package can be
imported right from brownie
and it has this function from abi
that allows us to
get a contract from its abi and its
address
so we'll just give it a name
we can say contract
type dot underscore name
we do the contract address
and then
the contract type dot abi
so these mock v3 aggregators and all
these contracts
have a dot avi
attribute that returns the api
they also have a dot underscore name
which returns their name so this is
perfect this is how we'll get the
contract otherwise and then at the end
of all this we'll just do return
contract awesome so this is an
incredibly powerful function for us
to get a contract based off of if it's
already deployed as a mock or it's a
real true contract i know there's kind
of a lot here but definitely check the
github repository if you're a little bit
confused on what's going on with this
function and let's
and let's also just deploy this to make
our linter happy why not
yeah vs code's happy now but now that we
have this function let's go back to our
deploy lottery
now we can do a comma get account
and now we have a get account function
so let's go through this again
this lottery.deploy getaccount is going
to get an fusd price feed
if we don't have a mock deployed it's
going to deploy a mock price feed for us
and we're going to return that mock
price feed
however if we're on a test net if we're
on a real network we're going to grab
its actual address and return
a mock contract of it our mock contract
here has all the same functions of a
regular contract so we can just use it
as the same this way we don't have to
adjust this function for whether or not
we're deploying to a test net or to an
actual address the only additional piece
we should put in here just for clarity
is we should add dot address here
because this is going to return the
actual contract and we really only want
the address this is going to make our
coding a lot more robust for
moving between development environments
and test environments and working with
scripts in a really effective manner so
now that we have this incredibly
powerful function let's go back to the
lottery and figure out what are the
different pieces we need in here okay
great we also need a vrf coordinator
so
to do this we're going to go back to our
docs.chain.link
we'll go to contract addresses
and we could do mainnet here but let's
also just set this up to work with rank
b so we'll do ctrl f for rink b
vrf coordinator is going to be this
address right here so we'll copy it
we'll go back
and we're going to have to do
in our config
is we're going to have to add a new
network here for rank b
we'll do vrf core data nato
will be that address right there
and then while we're doing this let's
also get the rink b address for our
price feed so ethereum price feeds
rink b
let's scroll down for fusd
fusd here we go
grab that
enter this will be f usd
price feed
face adder sit here perfect
so now we can do get contract
vrf coordinator dot address of course
we are gonna have to go back to our
helpful scripts
because there's currently no mapping
between what a vrf coordinator is and
what its mock needs to be so we'll add a
comma here
and we'll do vrf coordinator
and we need to get
a mock vrf coordinator well first of all
we don't even have our mach v3
aggregator so let's go grab that as well
so we can grab both of these again i'm
going to highly recommend going to the
chain link mix
going into the contracts here going to
the test folder for these different
mocks because these are already set up
to work with the chain link mix however
you can definitely go into the chain
link github as well
go to contracts
src
0.6
tests
and then look for the different mocks in
here so mock oracle vf coordinator mock
et cetera so we're just gonna i'm just
gonna grab it though from this chain
link mix so let's go to vrf coordinator
mock
and i'm just gonna grab this whole thing
here
so i'll do contracts new folder
test
new file vrf
core
core
[Music]
moc.sol
paste it in here
and then while we're in here we want to
do new file
mock v3 ah
greg
sol
we'll grab this as well
from our chain link mix
again it's got all the functions of a
price feed update answer
latest round etc
vrf coordinator walk has different
functions for actually working with the
vrf coordinator
one of the specific ones in particular
is this callback with randomness that
we're going to use
in our tests so our vrf coordinator is
going to get mapped to
our vrf core
nator mock
which will also import this
from brownie
great and just to double check
everything's working we'll want to run
just a quick brownie compile
make sure we are importing our mocs
correctly and everything is compiling so
it looks like we're good there
all right
so now we have
git contract vrf coordinator dot address
perfect what else do we need in here
we need a link token the chain link
token is of course just another smart
contract so we're going to do the exact
same thing here
get contract
link token
dot address
of course this means
in our config
for rink b
let's add a link token address
we'll go to the chain link documentation
go to
link token contracts
look for rink b
we'll grab this address
we'll drop it in here
perfect now we have it in our brownie
config
we'll also need to add it to our
helpful scripts
so we'll need
a mock link token
which again
we can just go ahead and grab
from our chain like mix here
so we can go to test and as you can
probably see what i often normally do is
literally just copy this entire test
folder project to project
so i'm going to copy this whole thing
create a new file
we're just going to call this one
link token.sol
contract link token perfect
and then in our helpful scripts we're
going to have this be linked token
and of course we're going to import this
from brownie
great git contract link token.address
perfect
what else do we need we need a fee and a
key hash so the fee and the key hush are
both just numbers right these aren't
actually contracts so we don't need to
put this through that get contract bit
what we can do
is just in our config
and our development network
we just add a default for the key hash
and for the fee
i'm just going to set my development key
hash and fee equal to the rink b ones
so to grab
those go to the chain link docs once
again we'll scroll down to using
randomness
contract addresses
we'll look up rink b
we'll grab the
key hash
here which we'll paste in for both
are development
and rink b
and then the fee it says 0.1 link so
we'll just do
that in way here which will be one
one two three four five six seven eight
nine ten
one two three four five six seven
and we'll do this
line for ring p as well
now in our deploy lottery we can just
grab this directly from a browning
config because we're always going to
have this default key hash and this
default fee here for our development
network
so we'll do config
networks
network dot show active
which one's first the fee
fee
of course this means we're going to
grab network from brownie
and also config
then we'll do config
networks
network dot show active
and then of course
our last bit here
from
account
and then additionally as we learned last
time if we want to publish this
we'll do publish
source
equals config
networks
network dot show active
we'll say dot get
verify
and then we'll add this false bit here
what this is saying is get that verify
key
but if there's no verify key there just
default to false this way if we don't
set a verify key in development that's
fine it just won't get verified for ring
b let's go ahead and set verify
to true
so we can actually verify this on the
rigby chain
and then we'll even do a print statement
here
deployed
lottery
all right lovely let's try this out
we'll do brownie
run scripts
deploy lottery.pie we won't set a
network flag so it will go to the
default development network let's try
this out
things are compiling ganache is spinning
up
it looks like we did run into a little
issue here with our our get contract
function
ah of course we forgot to add deploying
these mocks in our deploy mock script
whoops let's go ahead and add that as
well
right now our deploymox only deploys the
mach v3 aggregator
so let's add the rest of our mocks in
here
we're going to need to deploy a vrf
coordinator mock and a chain link token
mark so let's open up those contracts
see what they need
a link token
for a constructor
doesn't have a constructor so we can
just have it be blank
so we'll do
link token
dot deploy
and all we need is a from
account here
and then let's see what that vrf
coordinator mock takes
prf coordinator mock
it takes the link token as an address
perfect
so then when we deploy the link token
here
we'll say link token
equals link token.deploy and then we'll
do vrf
core
donator mock
dot deploy
ploy
and then we'll use the link
token.address
as an input parameter
and then of course from
account
all right so now we're deploying all
three of those mocks right away
let's try this again
brownie run scripts
deploy lottery.pi
ganache is spinning up
perfect
so we can see here that our mach v3
aggregator was deployed
then our mock link token was deployed
then our mock vrf coordinator was
deployed and then our lottery was
deployed with those mocks defined
and we deployed the lottery awesome
now we could 100 percent
go ahead and then run this script on an
actual test net right because our config
is set up well let's write some more
functionality for actually interacting
with this lottery
before we actually do that and then we
can actually just run a script which
will do all this functionality end to
end because again deploying to testnet
takes a long time and we really only
want to do that when we're done and
we're fairly confident that everything's
working well let's even just delete this
here
so now what's the next thing that we'd
want to do here what's the next thing we
want to do in a script here well we'd
probably want to go ahead and start the
lottery so let's write a script that can
actually do that
we'll do def
start lottery
and then here we get our account
equals get account
we'll say the lottery is going to be the
most recent deployment
of the lottery
and we're going to call this start
lottery function here this is indeed
changing state so we do have to make a
transaction
we'll do lottery
let's start
lottery
we'll say from
account
then we'll do a little print and just
say
the lottery is started
and then in our main function down here
we can even call this start lottery
function
so if we run this
again on our development chain
we'll see if everything works smoothly
here okay we did run into an issue and
this is something that you'll see from
time to time
typically the workaround is you want to
wait for that last transaction to
actually go through so we'll say
starting
transaction
equals lottery.start lottery it will do
starting
transaction.weight
1.
brownie sometimes gets a little confused
if you don't wait for the last
transaction to go through
so let's try it again and perfect we do
get this working as intended so that is
really helpful helpful tip if you run
into those weird issues you'll notice
that even when we didn't have this it's
still completed successfully i just got
a little confused at the end
all right cool so what do we want to do
next well we probably want to enter the
lottery let's do def
enter
lottery so how do we enter the lottery
say account equals get account
lottery is going to be
lottery
minus one
we need to pick some value to send when
we call the enter function
right because we need to send that
entrance fee with it
so we'll say value equals lottery dot
get
entrance fee
and just to be safe i usually will tack
on a little bit of whey as well because
sometimes it might be off by like one or
two or something like that so we'll do
lottery. get entrance fee plus you know
maybe something like this which is like
barely anything then we'll do
transaction equals lottery.enter
do from account
send a value which will be value
we'll do tx.weight
and then we'll do print
you entered the lottery
and we'll do this enter lottery bit down
here too enter lottery
we'll run this see if our enter script
is working appropriately
you entered the lottery looks great and
let's do our last function here we'll do
def
end lottery
count equals get account
lottery equals
lottery minus one we'll make a
transaction which will be lottery dot
end lottery
now before we actually end this lottery
we're going to need some link token in
this contract
because remember our end lottery
function
calls this request randomness function
and we can only request some randomness
if
our contract has some chain link token
associated with it so we're going to
need to first
fund the contract
and then
end the lottery since funding our
contracts with the link token is going
to be a pretty common function that we
use let's go ahead and turn this also
into a helpful script
so let's go to our helpful scripts we'll
make a new function
called fund with
link
and let's have this take a couple of
parameters so first we'll want to have a
contract address of course
we'll want to know who we're going to
fund with link we'll set a default
account to being none
so if you want you can send an account
but you don't have to if you don't want
to we'll also do the same thing with a
link token we'll say if you want to use
a specific link token you can otherwise
we'll just grab it ourselves
and then we'll also do a default amount
which we'll set to
1
one two three four five six seven eight
nine ten one two three four five six
seven
which is going to be
0.1 link
so first let's get an account we'll say
account
equals
we're going to do a little clever python
stuff here
we'll say account equals the account
if somebody sent it
if account
so we're saying
the account that we use
is going to be
this account thing if this account thing
even exists otherwise we'll call our get
account otherwise we'll just do our
regular get account function
then we'll do the same thing with the
link token
say the link token
is going to be equal to
the link token
that somebody supplies as a parameter
if
they applied something as a parameter
otherwise we'll just do that get
contract stuff that we did before
of the link token
now that we have this link token
contract from our get contract function
which again is basically the equivalent
of doing which again is doing this
contract up from abi on our link token
pulling from
our config or from our mock now we can
just call the functions on this link
token so we can say our transaction
equals
link token
dot transfer
we're going to transfer token to
the contract address
with a certain amount
and of course we'll do from
account
we'll do tx.weight
and then we'll do print
funded contract
and then we'll even return that
transaction
i do however want to show you another
way to work with this using the
interfaces instead of doing this
linktoken.transfer directly on the
contract we can use this interfaces
section
to actually interact with some contracts
so right now we have our mock link token
in here which is great because it has
all the definitions and all the
functionalities defined in here
sometimes you're going to have contracts
that you don't have everything you don't
have all the functionality and maybe you
only have the interface maybe you only
have some of the function definitions so
we can still interact with contracts
with just an interface because again
that interface will compile down to our
api
so as another way of teaching us how to
actually work
with some of these contracts
what we can do
is we can use we can use the link token
interface basically the same way as we
used the link token contract here so
again i'm in my chain link mix because
there's already a link token interface
in here and this will compile down to a
way that our brownie package knows how
to interact with these contracts
so if you wanted to we could just grab
this
go to our brownie section
we'll do a new file in interfaces
we'll call it link
token interface
dot soul
we'll paste it in here
save my auto format auto formatted here
and what we can do in our helpful
scripts instead
is transaction
equals interface
and we can also just import interfaces
right from brownie
interface dot
link
token interface
and we just need to give it
a contract address so we can say link
token dot address
excuse me we could say
link token
contract equals interface dot link token
interface link token dot address
so this is another way we can actually
create contracts to actually interact
with them
so we saw up here
this contract.from abi which is great
this is another way we can do that exact
same thing so then we can just do
linktokencontract.transfer
contract address
amount
from
account
so this is tx equals
so this is another way to actually
interact with contracts that already
exist you're probably starting to see
that brownie has a lot of built-in tools
that make it really easy for us to
interact with contracts if we have the
api we can just pop it into
contract.from avi and again with the
address and the api and then just give
it some name if we have the interface we
don't even need to compile down to the
api ourselves because brownie is smart
enough to know that it can compile down
to the api itself and we can just work
directly with that interface which is
incredibly powerful for now
i'm going to comment these two lines
though and we'll just use the
linktoken.transfer for now now that we
have a funding script or a funding
function we can import this from our
helpful scripts
from scripts.helpful scripts import get
account get contract
fund with link
and we can just call in our end lottery
function
we'll do fund with link
and parameters we just we only really
need a contract address because the way
we set this up we'll just automatically
grab a default otherwise so we can say
lottery dot address
and that's it that's all we need and
then i know we're doing tx.weight right
in the fund with link but just for to be
verbose here
we'll get the transaction from the fund
with link and we'll do tx.weight here as
well
and then once we're funded with link
then we can go ahead and call our end
lottery function because again this is
going to call that request randomness
function from the vrf we'll do
end
ending transaction
equals
lottery dot end
lottery and all we have to do is from
count
to ending
transaction.weight
one
so from our end this is really all that
we need to do
right but remember
when we call this end lottery function
we're going to make a request to a chain
link node and that chain link node is
going to respond by calling this fulfill
randomness function
so we actually have to wait for that
chain link node to finish
now typically it's within a few blocks
so normally what we can do is we can
just do a time dot sleep
for something like 60 seconds
and typically in that time the chain
link node will have responded
so we'll just do import time
at the top
time dot sleep
and then
we can see
who that recent winner is if that chain
link node responded with a recent winner
so we can say print
f
lottery dot resent
winner
is the new winner
all right now of course for those of you
who are thinking ahead a little bit you
might be thinking hey well there's no
chain-link nodes watching our local
ganache
and you're exactly correct so what
happens when
we add
our end lottery function
to our main function here
do you think that we're going to
actually get a recent winner back why
are we not what do you actually think
well let's give it a shot
do brownie run scripts deploy
lottery.pie
so we're doing a lot of transactions
here we've started the lottery we're
entering the lottery you entered the
lottery we're sending some link token
now we just called the end lottery
function
while we're waiting here
this is when the chain-link node would
go ahead and start responding with our
randomness however as you're probably
astutely telling however as you probably
astutely guessed
there's no chain-link node that's going
to call this fulfill randomness function
right now so for our grenache chain this
will hypothetically end
with nothing right because there's no
chain-link node actually responding here
zero is the new winner of course this
means that the chain-link node actually
didn't respond because there is no chain
link node on our local ganache for our
testing purposes we're going to figure
out how to actually get around that and
deal with that
awesome it looks like we have everything
set up to be successful in our lottery
here
but we want to do our due diligence we
want to make sure that our tests are
really solid on a development chain
before we actually test this on an
actual test then so let's jump into some
of these tests we've already started
with this testlottery.pi bit here but
we're going to iterate on this and make
this even better
now before we get into these tests
there's a couple of things we want to
talk about here and that's going to be
integration tests and unit tests unit
test is a way of testing the smallest
pieces of code in an isolated system
and we're going to use it to loosely
define testing independent functions in
our lottery contract
we also want to do what's called
integration testing which is going to be
testing across multiple complex pieces
typically i like to run my unit tests
exclusively on a development environment
and my integration tests on a test net
this is really helpful because we can
test the majority of our application
like we said on a development network
and then still be able to see what
actually happens on a real test net and
see what happens on etherscan and
everything like that
typically
what people do is in their side their
tests folder they'll create two
different folders one for unit
and another folder for intergration
since for this demo we're only going to
have one file for both i'm just going to
go ahead and not create these folders
but
but it's a pretty common practice
instead what i'm going to do is i'm
going to rename this i'm going to hit
enter to rename it
i'm going to do underscore type unit
for unit tests and we're going to create
a new file
called test
lottery
integration
dot pi so this one we'll do our
integration test and in this one we'll
do our unit tests now when writing unit
tests we really want to test
hypothetically every single line of code
in our smart contract this is incredibly
important of course because smart
contracts are open to everybody to see
and interact with so we really want to
test every single line of code we have
in here
so let's go ahead and let's go ahead and
finish writing a get entrance fee test
that will work on a local development
network as you can see we're already
going to have to refactor this from what
we originally had let's go ahead and
just delete everything under here for
now
we already learned so much more from
there all right so how are we going to
test this get entrance view function now
so first we're going to want to deploy
our lottery again
since we have
a deploy lottery script already
we can just use this deployed audio
script as well
if we wanted to we could just copy paste
this hold part into our test but
we're just going to go ahead and work
from this deploy lottery script so
we're going to import this and then we
can actually even
get rid of this from web3 line for now
we can get rid of these two comments too
and we'll say from
scripts that deploy lottery
import
deploy
lottery and on this deploy lottery
function would say lottery
equals deploy lottery
and we will return our lottery
now our unit test we'll say lottery
equals deploy
lottery
and this will give us our lottery
contract once we have our lottery
contract
we can just call this get entrance fee
so we can say entrance fee
equals lottery dot get
entrance fee
and oops let's just make sure we're
doing the arrange
act
assert mentality here
and we're going to want to make sure
this entrance fee is what we expect it
to be so what do we expect it to be
well
again our helpful scripts is going to
deploy these mocks right
it's going to deploy this mock and the
initial value is this 2000 number so if
the price
of eth here is 2 000
2 000 f usd feed and the usd
entry fee
is 50.
we'd say 2 000
over 1
is equal to 50 over x
which is going to be equal to 0.025
so we can go ahead and even do this math
here
we can say expected
expected
entrance fee
is going to be equal
to
it's going to be equal to 50 divided by
2000.
we'll just do 0.025
but we'll do this in
way so do from web3
import web3
we'll say this is web
3.2
way
0.25 ether
and now we'll assert
our expected entrance fee
equals
the entrance fee now to test this we'll
do brownie test k
and perfect this is working
exactly as we anticipated so that's
awesome now as we mentioned since this
is a unit test we really only want to
run this when we're working on a local
environment a local blockchain
environment or a local development
network so we'll go ahead and do this
with pythons again
so if network dot showactive
is not
in
local blockchain environments
pi test dot skip of course we're gonna
have to import pi test
we're gonna have to import this local
blockchain environments from our
scripts.helpful scripts my vs code
automatically added that bit here now if
we try to run this
brownie run
excuse me brownie test
dash k
get entrance fee dash dash network rank
rink eb it should go ahead and skip this
perfect that's what it does
what's the next piece that makes sense
here enter is going to be one of the
first things that these developers do so
let's do test def
test enter but let's even be more
specific than that we don't want people
to be able to enter our lotteries unless
the lottery is actually started so let's
make sure that this line actually works
so we'll call
def test
can't enter unless
started and again we're only going to
run this on a local development chain so
we'll just copy paste this section down
here we'll say lottery
equals
deploy
lottery because we're going to want to
work with the lottery and now we're
going to want to that when people try to
enter a lottery that hasn't started yet
it's going to revert so we can use what
we've used before we'll say with pi
tests dot
raises exceptions dot virtual machine
error
lottery dot enter
from
get account
value
lottery dot get entrance fee
of course we're going to import both get
account
from our helpful scripts
and exceptions from ronnie
perfect and this as well is following
the arrange
and this is actually act slash
assert so let's go ahead and test this
brownie test k
test can't enter unless starter
oops let's do start ed
and great that's passing as well let's
go ahead and keep going down this list
what else now we've tested whether or
not they can't enter let's test whether
or not they can enter so we'll do def
test
can
start
and
enter lottery
so we're going to copy this again
paste it down here since we're going to
work on a local blockchain
we'll do lottery
equals
deploy
lottery
account equals get account
we'll start the lottery
lottery.start
lottery
we'll do from
account
we'll do lottery.enter
from
account
save value is
lottery
dot get
entrance fee
and then we'll assert
that
we've correctly added a player to this
lottery so we'll assert
lottery.players
of zero is going to be this account
right because we have our players array
and we're going to assert
that we're pushing them onto our array
correctly
lottery.players 0 equals
account so here's our act
here's our assert
so let's try this now
brownie test dash k test can
start and enter lottery
and once again awesome things are
looking great
now let's test to see if we can actually
end a lottery so we've tested we can
start a lottery so we'll do def
test can and
lottery we're going to copy this again
paste it down here
do lottery equals deploy
lottery
account equals get account
we'll start the lottery with
lottery.start
lottery
now we could 100
just import the rest of these functions
in here like n lottery enter lottery and
start lottery and similar to how we're
just doing lottery equals deploy lottery
we could absolutely do that for being
very verbose here i'm just going to go
ahead and write all the functions and
transactions myself and this way we'll
actually be able to test a little bit
more granularly anyways
we'll do lottery dot
start lottery
from
account
do lottery dots enter
from
account we'll give it a value
lottery dot get entrance fee
so i'm gonna have to do account
course equals get account
now
to actually end the lottery we do need
to send this some link because we're
calling request randomness we use our
fund with link script
that we have in our helpful scripts
we'll import this from our helpful
scripts
we'll call
fund with link
on our
lottery contract
once we fund with link we'll then call
lottery dot
end lottery
from
account
and then how do we actually know
that this is being called correctly well
if we look back in our lottery contract
here when we call end lottery we don't
we're not really doing a whole lot all
we're doing is changing our state so
let's go ahead and check to see if our
calculating winner state is different so
we'll say assert
lottery
dot
lottery state
is equal to what
so calculating winner if we scroll up to
our enum
is in position two open is zero close is
one calculating winner is two
so we can say
assert lottery.lotterystate equals two
two
we can go ahead and test this as well
we'll do brownie
test k test can end lottery
we'll see if this works
and it does
now let's test the most interesting
piece of this entire lottery contract
we're going to test whether or not our
fulfill function actually works
correctly
does this correctly choose a winner does
it correctly pay the winner
and does it correctly reset so let's go
ahead and build our most
complicated and most important test of
this whole contract choosing the winner
we'll do def
test
can pick
winner
correctly
let's copy paste this bit
about getting started
we'll do lottery equals
deploy lottery
account equals get account
we'll do lottery dot start
lottery
from
account
and then we'll enter with a couple
different players we'll do lottery dot
enter
let's say from
account
value
lottery dot get
entrance fee
enter
and we'll copy this two more times
but instead
we use some different ids we'll do index
equals one
and we'll do index equals 2.
these are going to be different accounts
here because we're going to use a
different index
because we want to just test for
multiple different people here
this unit test is getting drastically
close to being an integration test but
as i said we're being a little bit loose
with the definitions here now we're
going to want to fund it with link so we
can just go ahead and copy this line
here
fund with link lottery
and now we're going to want to choose a
winner here
and this is where we actually have to
modify one more thing
in our lottery contract so in order to
test actually calling this fulfill
randomness function
and testing everything in here
we're going to need to call this fulfill
randomness function
now if we look at our vrf coordinator
moc
we have this function called callback
with randomness
and this is the function
that actually calls this raw fulfill
randomness.selector which eventually
will call that fulfill randomness
function but this is the entry point
that the that the node actually calls
we have to pretend to be a chain-link
node and call this function
we're going to return
a random number of course we're going to
choose the contract we want to return to
but we also have to pass the original
request id
associated with the original call now in
our lottery contract
our end lottery function
isn't going to return anything
and even if it did it would be really
difficult for us to get that return type
in our python so what we want to do
to keep track of when this contract
actually entered the calculating winner
state is we want to do what's called
emitting an event events are pieces of
data executed in the blockchain and
stored in the blockchain but are not
accessible by any smart contracts you
can kind of think of them as the print
lines of a blockchain or the print
statements of a blockchain
we can go to this logs section which
also includes all the different events
now there's a lot of information here so
we're actually going to do an event
ourself just so that we can see what
this really looks like you can see here
that when we call this end lottery
function
in the logs if we scroll to the bottom
there's an event here called
randomnessrequest
this was spit out by the vrf coordinator
this was spit out by the vrf consumer
base that we inherited and it even has
some data that's already been decoded
one of those pieces of data is the
request id now to add an event we first
need to create our event type
so at the top we'll go ahead and do
event
requested
randomness
we'll say bytes 32
request id
so now we've identified
a new type of event called requested
randomness
it's really similar to the enum in this
regard
to omit one of these events
all we have to do in our end lottery bid
is we'll do omit
requested randomness and then request id
because requested randomness takes a
bytes32
as an input parameter
and we're going to pass it that request
id as an input parameter now that we
have this event being omitted back in
our test when we call
end lottery it will actually omit one of
these events to our transaction
so what we can say then
is transaction
equals lottery.nd lottery
same way we've always done it
but now we can look inside of this
transaction object
inside of this transaction object is
actually an attribute called events
which stores all of our events we can
then look for
a certain event name which we know is
requested randomness so we'll say out of
all the events look for the requested
randomness event
and in there
in that request randomness event
find the request id
request id
now we can say request id
request
id
is going to get grabbed from this
event that we omit so these events are
going to be really helpful for writing
tests these events are also really
helpful for a number of other reasons
one of the big ones is is upgrading our
smart contracts or understanding when a
mapping is updated but for now we're
going to be using them for testing now
that we have this request id what we can
do is pretend to be the chain link node
and use this callback with randomness
function to dummy getting a random
number back from the chainlike node so
what we're going to do
is we're going to call our getcontract
function
and get that vrf coordinator
of course we're going to import it
from our helpful scripts
and we're going to call that callback
with randomness function
so we're going to do dot callback
with
randomness
and we need to pass it
this request id
a random number
and then the contract to return to
so we'll do request id we'll do some
random number
like we'll say static
rng
equals 777.
so we'll say the random number that
we're going to return is going to be 777
and then we'll do lottery dot address
because we're going to return it to the
lottery
once again we're going to say from
account because this is making a state
change and now that we've got a call
back what we can do is do our asserts
now so this
is us dummying getting a response from a
chain-link node and this is how we mock
responses in our tests to make our lives
way way easier
so now we can do we can figure out who
the winner of this lottery actually is
if these are our three enter entries
that means it's 777
mod 3 since our random number is going
to be 777
if we pull out a calculator
777 divided by three
it divides evenly so we know that this
means the answer to this is going to be
zero
aka our account is going to be the
winner
so let's assert
the lottery dot
recent winner
is going to be equal to our account
right because
we set a recent winner
in here
we transfer them some money
we'll assert
lottery.balance
is now zero because we're transferring
this account all the money
and let's even make sure that the
account gets more money right so we'll
do
starting balance
of our account
starting balance of account
equals
account.balance
count balance and we'll do balance
of
lottery
equals lottery dot balance and then
we'll assert
account dot balance
is now going to be
these two added together
started balance of account plus
the balance of the lottery
because we should get all of the lottery
winnings here okay so this is a long
test but this is probably the most
important test let's make sure
this is doing what we wanted to do so
we'll do brownie test k
test can pick winner correctly let's see
if this works
oops i forgot to put a
put some parentheses here let's
parentheses here
let's try this again
and perfect
we are actually updating paying out and
running our lottery correctly and fairly
with true randomness this is incredibly
exciting and we've emitted events in our
lottery contract to use in the off chain
event logging of ethereum i know we're
getting antsy
to actually run this on a real chain
so let's go ahead and do our last bit
here create our integration test which
we will run on an actual chain and then
if we wanted to we go ahead and try our
deploy lottery function on a real chain
as well all right so let's do our
integration test here this is where
we're going to actually test on a real
live chain we're going to use ring
because that's the network that we've
been using this whole time which is
great now i'm being a little bit liberal
in the way that we're doing our tests
here and we're just going to do one test
for this integration test but keep in
mind you're going to want to test every
piece of your code so let's just create
a test called def
test
can pick
winner
now this is going to be
the opposite of our unit test
our unit tests are only going to be on
our local blockchains right we're going
to skip if it's not on our local
blockchains
we're going to do the opposite of this
one
so we can even just copy this or we can
type it out we'll say if
our network
dot show active
is in those local
blockchain environments
then we're gonna do pi test
dot skip
of course since we're grabbing these
pieces we're gonna do from
brownie import
network
we're going to import pi test
and we're going to do from scripts
dot
helpful scripts
import
local
blockchain and by enronments
we're going to deploy our lottery so
lottery equals deploy
lottery
which we're just going to grab from
scripts deploy lottery
import deploy
lottery
we'll do account equals get account
of course we're going to grab that from
our helpful scripts as well
so we'll do lottery
let's start lottery
this will be from
account
do lottery.enter
say this will be from
account
we'll do some value which is going to be
dot lottery.get entrance fee
and if we run into an issue here
sometimes again we can do lottery dot
get interest fee plus like 100 or a
thousand or something like that this is
going to be barely any way but
for now let's keep it like this
then let's just copy this line
right again we'll have two people enter
the lottery
of course it's going to be us both times
and great
now we're going to want to actually end
the lottery so first we're going to want
to fund it so let's import that funding
script so we'll get fund with link or
that function
so we'll call our fund with link
function on our
lottery contract here and then we'll go
ahead and end the lottery so we'll say
lottery
dot
and lottery
we have to do this
from our main account we have to do this
from the admin account
now this is where it's going to be a
little bit different from our
integration tests
or from our unit tests
in our unit tests
we pretended that we were the vrf
coordinator and we called the callback
with randomness we pretended that we
were a chain-link node
here we're not a chain link node because
we're on an actual network so we're
actually just going to wait for that
chain link node to respond so for
simplicity we'll just do time dot sleep
and we'll wait like a minute for it to
respond
of course since we're using time
we're going to want to import time right
at the top
and then since account was the only one
to actually be in this
we'll do assert
lottery
recent winner
equals equals account
and we'll also assert
lottery.balance
0. all right great so we have an
integration test that we can run which
is going to run through pretty much the
vast majority of our functionality here
so we can go ahead and test this with
brownie
test
will be a little bit verbose here we'll
say dash k
test can pick winner
and then of course we'll do dash dash
network
rink b now before we run this
per usual we got to make sure do we have
any test that ring the ethereum we do
great do we have any test net chain link
we do perfect we have a dot env
we do it's got all of our pieces let's
check our brownie config
dot env dot env awesome and again if you
don't want to use the dot envy
you can use that other method that we
showed you guys how to encrypt with a
password that you can actually use
oops before we run this
let's set this to start lottery because
that's the
actual function here and we'll also need
to be lottery.balance with parentheses
here sorry about that and now we can run
brownie test dash k
fast can pick winner dash network
rink b
we'll also add this dash s flag which
will print out whatever brownie is going
to be printing out make everything a
little bit more verbose here and if you
want to you absolutely should because
this is something that we'll have to do
at some point anyways however if for
this tutorial you want to skip it go
ahead because we're actually going to
run through this whole process of
deploying and waiting again anyways so
now we've added all of our tests what we
can do is run our entire test suite
so we'll do brownie
test
and this is going to run through all of
our development tests here you'll see
it'll go really quickly
and you see how much faster it is for us
to run our test on a local chain as
opposed to doing everything on a test
map so it's going to make your life way
easier and we have everything passed
here so we know that our contract code
is doing approximately what we wanted to
do
so
it's time for the moment of truth let's
deploy this to an actual test net so we
have our deploy lottery script which
oftentimes
i'll have it be just this deploy lottery
bit and then i'll have some other
scripts for these other pieces or maybe
i'll do it in the brownie console
but
just to demonstrate everything end to
end we'll have deploy lottery start
lottery enter lottery and end lottery
all in this one script
so that we can see everything end to end
and see what it looks like on etherscan
so let's go ahead
and run this script on a ringbeat
network and then we'll go jump onto
etherscan and see everything
so let's do it brownie run scripts
deploy lottery
network ring can be
so first we went ahead and we deployed
our lottery we got our addresses with
our get contract method
we got our fee we got our key hash
we got our published source and
everything here then we went ahead and
verified it because of this published
source
so if we grab this address lottery
deployed here
we jump over to
rank the ether scan
paste this address in here
we'll see
this contract with a little check mark
is verified
again we'll go to the read contract we
can see all the public variables and all
the public functions we can go to write
contract and we'll see all the
transacting functions that we can
interact with after we get verified
and things get deployed we went ahead
and called our start lottery function to
actually start the lottery we got our
little print line saying the lottery
started then we entered you entered the
lottery we then funded the contract with
link so we could get our random winner
back
and then right now our end lottery is
confirmed and we're just waiting this 60
seconds right because we did this
time.sleep and if we sit on this
contract if we go to transactions
and we refresh we can actually see some
of these different method calls over
here we can see we did a contract
creation
we started the lottery we entered the
lottery and then we recently ended the
lottery and you'll see
in our script here it says
zero x blah blah is the new winner which
is perfect right that means that the
chain link node actually responded we
can actually verify that by looking in
the contract
we'll go to read contract
we can go to the recent winner and see
somebody did indeed recently win we can
also go to events
and we can see some of the events that
we created
we can see this first event right here
is this requested randomness event this
is the event that we called we have this
end lottery here we can also see an
ownership transferred function that got
called this was called when we actually
deployed this in the first place
now a little bit more on these events
aka these logs right
so topic zero this hash represents this
entire event right here
and this
bit is going to be our topic one our
first topic which represents that
request id
so this is going to be the request id
awesome we have successfully created a
working smart contract lottery with true
provable randomness this is absolutely
insane incredible job here now one
additional piece that i want to talk
about before we jump off here
is again in our testing
a file that you're often going to see
is what's called conf test dot pi python
automatically knows to look for this
comp test file and we'll grab different
functions from it we can also add
external plugins
fixtures hooks testing root path it adds
a lot of really fantastic features and
is a common thing that you'll see we
skipped over in here for simplicity but
in future projects you'll probably see
this comp test file which has a lot of
really nice testing configuration pieces
in it
now that was a lot of stuff to code and
quite frankly i don't think any of us
want to have to do that every single
time have to code everything from
scratch now you can absolutely get clone
all these repositories right from their
github but there's actually an even
easier way first to start with a blank
project here and this is with brownie
mixes so if we google brownie mixes
github we'll get this mixes organization
which just has a ton of boilerplate code
for us to go ahead and get started and
start developing the one we're going to
be working with is this chain link mix
piece which is forked from this official
one here this gives us some wonderful
contracts some tests a browning config
and really everything that we need to do
to get started so if you have brownie
installed
we can just bake this mix so we'll do
brownie
bake
chain lick mix and in our new empty
directory here
we'll get this new chain link folder
with everything inside of it so then we
can see the chain link
and we can see it has all these pieces
in here here already
in the contracts we have a whole bunch
of different samples of working with the
vrf working with the price feed
working with this thing called keepers
to automate our smart contracts and
making api calls and delivering any api
call that we want to the blockchain it
also has a brownie config which already
has a number of wonderful pieces in each
one of these networks so that we don't
have to go copy paste and add it in here
it's even got support for test nets like
avalanche polygon
finance and more it has a number of
really powerful tests including testing
some price feeds it has a whole bunch of
deployment scripts some mocking scripts
some helpful scripts and really
everything that we need to get started
and get going for starters we can run
brownie test
and it's going to compile everything
and then on a development chain run all
these
unit tests and if we wanted to test this
on a real test net we could do brownie
test dash dash
network ring b or any network that we
wanted if you're looking for a good
starter place that has a lot of really
powerful smart contracts for you to get
started i highly recommend using this
mix as a boilerplate starting point for
any of your contracts or any of your
projects here
now we are cooking so we've learned a
ton of the fundamentals of working with
brownie and working with smart contracts
now that we have kind of all the
building blocks though we can actually
code a lot of these much faster and much
more efficiently than before one of the
things that we've seen over and over and
over again is working with tokens and
the erc20 token standard
we're going to learn how to build our
own token before we do that let's
understand why we'd even want to do this
now first let's define even what are
erc20s so erc20s are tokens that are
deployed on a chain using what's called
the erc20 token standard you can read
more about it in the erc20 token
standard here link in the description as
well but basically it's a smart contract
that actually represents a token so it's
token with a smart contract it's both
it's really cool tether chain link uni
token and die are all examples of erc20s
technically chain link is in the rc677
as there are upgrades to the erc20 that
some tokens take that are still
backwards compatible with erc20s and so
basically you can think of them as
erc20s with a little additional
functionality now why would i even care
to want to make an erc20 well you can do
a lot of really cool stuff with it you
make governance token you can secure an
underlying network you can create some
type of synthetic asset or really
anything else in any case how do we
build one of these erc20s how do we
build one of these tokens well all we
have to do is build a smart contract
that follows the token standard all we
have to do is build a smart contract
that has these functions it has a name
function a symbol function decimals
function etc all these functions we need
to be able to transfer it we need to be
able to get the balance of it etc and
again if you want to check out some of
the improvements that are still erc20
compatible like the erc677 or the erc777
you definitely go check those out and
build one of those instead so let's
create a new folder and get started
we're going to create our new browning
file of course with brownie init it's
going to start up our repository and
start up everything that we are going to
work with here we can kind of actually
just jump in and start right with our
contracts so let's create a new file and
we'll call it our token
dot sol
and this is where we're going to add all
of our token code
now since this is an eip right this all
this is is a smart contract so what we
could do is we could grab all these
functions
copy and paste them in here one at a
time
grab the name
grab the symbol
grab the decimals and then you know code
all these up be like this does some
stuff blah blah blah or
we could do it the much easier way right
since we're engineers we don't always
want to reinvent the wheel so once again
our friends at open zeppelin
have some amazing contract packages for
actually building our own erc20 token so
we can go right to the opens up and
documentation i'm working on the 4x
version but again it doesn't matter the
version that you use so long as in our
config file we add the version that
we're going to use which again we've
already gone over so let's go over to
their erc20 documentation and this is
the entirety of the code that is needed
to make an error c20 so we can just go
ahead and even copy this
paste it in here and boom
we have some erc20 code in here let's
actually just change the name of
everything in here though so we're going
to call this our token
dot sol
we have
this spdx license identifier mit great
we're going to be using solidity version
0.8 which i know i've done a lot of this
code actually in point in 0.6 but i
highly recommend working with 0.8
because it has a lot of really fantastic
improvements to solidity you'll notice
this is our first dive into using a
different version of solidity here
you'll notice that most of the syntax is
exactly the same there are like i said a
couple of nice improvements with 0.8 the
main one being you no longer have to use
those safe math functions that we talked
about before but then we're going to go
ahead and import opens up when contracts
token erc20.sol now of course since
we're importing open zappone we're
importing this package we've got to add
this to our browning config
diamo
and before we even get started you
technically have all the tools that you
need to code and deploy your own erc20
token now i'm actually going to
challenge you to go ahead and try to
start a browning project create your own
token using opensupplement packages and
then deploy it on a test net i'm going
to show you how to do all of it here
anyways but challenging yourself and
trying to do things your own and
exploring is really one of the fastest
ways to learn and grow in this space
did you give it a shot no really pause
it now and give it a try
all right welcome back now we'll go
through it and we'll do it together
of course we need to add these
dependencies
open zeppelin
open
zeppelin contracts
let's do their version four
so let's even go to github
open zeppelin
and we'll do
4.2.0 which was released yesterday at
this time which is great 4.2.0
and of course again compiler
we'll have silk
remappings
we'll add
at open zeppelin
equals
this
and then we're going to go ahead and
save
now we can use this at opens up line and
it will refer to the opens up and
contracts here so great now we can go
ahead and import these
let's change the contract name to our
token we're going to inherit this
erc20.sol from open zeppelin we can even
go ahead to opens up on contracts github
and we can even see what this erc20
looks like so we can go to
their contracts down to token
erc20
erc20.sol
and this is their initiation of an erc20
which has all these functions like name
symbol
decimals total supply etc in our
constructor we're going to add an
initial supply which is going to be in
way of course so the initial supply of
that token and we're going to use the
constructor of the erc20.sol which again
we can go ahead and check in the code
here and we can see the constructor uses
a name
and a symbol
so we have a name we'll call it r token
and the symbol will do ot and boom that
is literally all we need for our token
here i told you this is going to be a
much faster project now for scripts all
we have to do is create a new file
we'll add a 1
deploy token dot sol and we'll also add
a helpful
scripts apply
excuse me this deploy token dot pi
excuse me
we'll just quickly add a account
function we'll say def get account and
you can go ahead and just copy paste
from the last one and if you want you
can actually just copy paste from our
last helpful scripts because it's pretty
much going to be exactly the same so we
have all these wonderful
ifs statements so that we can deploy
from really anything that we want now in
our deployment token script we'll do
from
brownie
import
our token
and then from
scripts that's
helpful scripts
import
get account and just to make sure let's
add an init
dot pi in here
just to make sure that our scripts can
actually import so since we know
since we know that we need an initial
supply here let's go ahead and do
initial
supply
equals and then we can do you know
whatever we want here
if we want to make it a little bit more
readable we'll also
do
from web3
import web3
and we can do
web3.2
way and we'll say
1000 as the initial supply and this is
in ether
so our initial supply is going to be
1000 ether
then we just add our main function
we do account
equals get account
we do our token
equals
our token
dot deploy
we just add as a parameter
this is initial supply
do from
account and then we'll do print
our token dot
name
and that's the whole function now of
course if you don't have your
environment variable set we're going to
add our dot enb file
this is where we can add our private key
our web3
infiera
project id and then if we want our ether
scan token i'm going to skip doing this
for now because my environment variables
are already set
and then last but not least we'll add
dot env
dot env
so private key equals ox blah blah blah
when three inferior priority equals blah
blah blah ether scan token equals blah
blah blah
and perfect now if we want to actually
deploy this to a testnet all we have to
do
go into our config
we'll add wallets
from key
we'll add our environment variable
private key
now brownie knows where to grab this
from because we've defined it in our
helpful scripts what i can do now
so brownie runs scripts deploy token.pi
and we can go ahead and see that our
token is printed out
we can see that we have this token
deployed on our local ganache
we can see our token here and this is
great now i can go ahead and run
this again
network ring b
now if i grab this address go to the
ringby ether scan
pop it in after a quick refresh i can
now see that
my contract has indeed been added and
etherscan even picks up that it's a
token
now we could do we can grab this and
grab this contract address
go to assets
add it in our metamask here
next
add tokens and you'll see we are the
proud owners of 1000 hour tokens now
something else that you might want to do
is add this to a liquidity pool or add
this to a place where you can actually
go ahead and sell it and put it on the
market you can do something like that as
easily as just popping onto uniswap
going to pool hitting more
create a pool
and then adding our token in here we'd
have to manage the token list and be
sure to add the token in here but we
could go ahead and add a token
create our own pool and automatically
put it on your swap and that's how easy
it is to actually sell it on one of
these pools but alright so this was
probably our easiest project of the
course but it really shows how far
you've come along everything here
i thought we know a little bit more
about d5 and why it's such an amazing
amazing technology that only works in
the blockchain world let's look at this
site d5 pulse or if you want to look at
another one uh there's another fantastic
one out there called defined llama which
also shows a lot of these different
protocols in here so defy pulse is an
application that shows some of the top
d5 projects based on how much
total asset is locked into each protocol
ave which currently is the number one
ranked d5 application with 9.32
billion in assets under management in
terms of usd then we have some fantastic
ones like curve compound maker instadap
etc now we're going to be looking at two
of these protocols in particular the
first one of course
being ave and the second one is going to
be a type of what's called a
decentralized exchange you start with
ave we're going to go to testnet.ave.com
dashboard and it'll bring us to a screen
that looks something like this with
please connect your wallet and
everything will be pretty empty parasop
is what's known as a dex or a
decentralized exchange it allows us to
trade tokens incredibly easy on the
blockchain now there's not a whole lot
of test net indexes that actually work
so we're just going to look at them and
simulate as if we were working on them
for example if i wanted to trade one eth
for some usdt or maybe some wrapped
bitcoin or some dye or some ave
or link or really any token that we
wanted
all we would need to do is connect our
wallet here
and
a swap button would show up and we would
go ahead and hit swap some other really
powerful these dexes and really popular
ones are going to be curve finance
uniswap and it's a really really easy
way to go ahead and swap your tokens for
one another depending on what you're
looking to do ave is incredibly powerful
and it's going to be one that we're
going to be working a lot with because
it has pretty much all the fundamentals
of working with the d5 protocol that
we're looking for and it has a test
stand that we can go ahead and test and
simulate actually working with some of
these protocols so we're going to first
work with the ui or the user interface
and then we're going to do everything
here programmatically first things first
if you don't already have it make sure
you have some test net ethereum at least
and again you can get some test and
ethereum from looking at the link token
contracts
and going to coven
this one indeed uh the test net of ave
right now is only on coven so we're
going to go ahead here
we're going to add our copy our address
paste it in
i'm not a robot
70.1 test eth remember we use this
linked token contracts page because this
is going to have the most up-to-date
faucets here once we see some eath in
our coventestnet here we can go back to
ave
so whereas paraswap allows you to simply
swap between assets and do a lot of
buying and selling of tokens
ave is a lending and borrowing
application so we can actually put down
a token as collateral and we can borrow
and we can generate some yield from
interacting with this protocol borrowing
and lending is a critical piece to doing
any type of really interesting financial
applications or financial instruments
such as short selling being exposed to
more assets etc
you can also gain some percentage back
if you look at apy
it'll tell you how much percentage over
a year you'll actually get in returns
from staking or depositing an asset
so here's what we're going to go ahead
and do we're going to connect to the
application
using metamask and you'll see on the
deposit tab here we'll see our balance
be 0.1 each because that's how much i
currently have in my wallet right now
what we can now do
is click on ethereum click this max
button to deposit some ethereum
we'll hit continue
and a little dashboard will pop up
asking us okay would you like to deposit
clicking this deposit button will
actually have us deposit right onto the
ave contract on the coventest net make
sure once you hit deposit here that
you're actually on a test net here it
looks like i actually have some
insufficient funds so i'm actually going
to go
borrow a little bit more
or from the faucet here
grab a little bit more from the faucet
here
we're going to come back
we're actually going to go back
refresh and now it says i have
0.1
we're going to deposit 0.1
continue
deposit and metamask is going to pop up
saying hey are you sure you want to do
this right we can check our data
we can grab this address even if we want
pop it on to
coven.etherscan
paste it in here
we can even double check to make sure
that this is indeed the right contract
that we want funnily enough you'll see
that this is the west gateway when we
deposit our covent eath it actually gets
transferred into an erc20 version of our
ethereum and then it'll go ahead and
deposit it into the ave contract so
we're going to hit confirm
now we're going to get this pending here
we have a link to the explorer
which shows us this transaction that's
going through and then we'll see that
we've indeed successfully deposited our
ethereum now down here you'll see a
little button add a eth to your browser
wallet and we're going to go ahead and
click this
and this will automatically add this
token
to our wallet so we're going to hit add
token
and we see now in assets we have this ae
down here
we could also have manually hit added
token got the contract address but avi
was nice enough to just go ahead and add
us a little button that does it for us
ae is what's called an interest-bearing
token and it goes up in real time you'll
see if i sit here long enough you'll see
this number actually continually going
up this is the profit given to us from
other people borrowing the eath that
we've deposited into ave if we go to our
dashboard now
we can see we have 0.1 each deposited
and if we roll over it you'll constantly
see the amount go up and up and up we
can go ahead and withdraw our eath
which will convert our a
back into eath with the additional
interest that we got from depositing so
depositing into ave will give us
interest back as a payment for other
people borrowing the eath that we've
deposited we can also use this eath as
what's called collateral so if i go to
this borrow tab
i can actually use the eath to borrow
some other acid maybe i want to borrow
dye which is a stable coin meant to
always equal one dollar usdc and usdt
also are meant to always reflect a
dollar we can borrow what's called
wrapped bitcoin which represents the
bitcoin price we could borrow some
ave token some bat token some link token
we can borrow all these different tokens
now borrowing an asset is incredibly
incredibly powerful by borrowing you're
allowed to obtain liquidity without
selling your assets and borrowing is one
of the first pieces in order to actually
short sell borrowing in default
protocols is absolutely massive because
it allows you to frictionlessly short
sell obtain liquidity without closing
your position
gain yield on some deposited collateral
you can do a massive number of new
things only in the default world such as
flash loans
now an important note on borrowing
assets on mainnet since we're just
borrowing it on test net and this isn't
real money this is 100 okay to
experiment with and work with however if
you borrow an asset and you do not pay
attention to how much you have for an
underlying collateral you could get
liquidated and lose some of your funds
so be very careful and pay a lot of
attention if you're going to do this on
an actual network now let's say we want
to borrow the ave token for example we
click here and we can choose the amount
that we want to borrow now here's the
thing
since we've placed down some collateral
right 0.1 if the amount that we borrow
ends up being too high
we'll actually get what's called
liquidated every time we borrow an asset
we get some type of health factor the
health factor represents how close to
being liquidated you are once your
health factor reaches one
the collateral that you've actually
deposited will get liquidated and
somebody else will get paid to take some
of your collateral this is so that the
the ave application is always solvent
being solvent means it's never in debt
so when i want to borrow i want to
choose some amount that might be a
little bit safe here and so that i'm not
going to get liquidated so
zoom in a little bit
i'm going to choose some number where i
see a health factor maybe like 5.6 we're
going to continue now we'll have to
choose our interest rate when we borrow
an asset we actually have to pay some
interest this payment is actually going
to go to the people who are depositing
die or depositing the asset the interest
rate that we're going to pay is actually
going to be paid to those who are
depositing the asset that we're
borrowing so like how we're getting
interest on our deposited collateral
others are getting interest on their
deposited collateral based off of how
often people are borrowing it we choose
a stable apy which will always be four
percent
or a variable apy which will change
based off of how volatile and how in
demand this asset is for now i'm going
to choose variable but you can pick
whatever you want especially for this
demo we're going to hit continue i'm
gonna zoom out just a little bit
and the same interface is gonna show up
we're gonna go ahead and hit borrow
metamask is gonna pop up and ask us if
we really want to borrow we're gonna go
ahead and hit confirm
and now we've successfully borrowed die
into our application we can even hit
this little add die to your browser
wallet
to add the token to our wallet
now if we hit the button we go to assets
we can now see die is indeed in our
token assets here now if we go back to
our dashboard you'll see we have a
health factor score here this is a
really important score if you click on
this little i thing it says the health
factor represents the safety of your
loan derived from the proportion of
collateral versus amount borrowed keep
it above one to avoid liquidation
and we'll see all of our deposits here
so we still have 0.1 in each deposited
we also have 28 die deposited you can
see a whole lot of different stats here
for working with our application we can
withdraw our die we can withdraw our eth
we can borrow more die or we can go
ahead and repay we can either repay from
our wallet balance or from our current
collateral yes we could repay with our
collateral
let's go ahead and do from our wallet
balance
we'll hit max
continue
and we even get this little thing that
says you don't have enough funds to
repay the full amount well why is this
the case we just borrowed this amount
it's because already since depositing
we've accrued a little bit of we've
accrued a little bit of extra debt
remember we hit that variable apy
and every second it's going to tick up
just a little bit so let's go ahead and
pay back what we can with our wallet
we're going to confirm
we're going to approve our data to be
spent
and then we're going to go ahead and hit
the repay button and gray now if we go
back to our dashboard you can see we've
repaid almost everything here but we
have a little bit left so let's just go
ahead and hit repay with our current
collateral we'll hit max
continue
and this will use our eth to pay back
the collateral instead of the die
and then we'll hit repay this way we'll
have no more debt
great now if we go back to our dashboard
we can see we have no more debt which is
fantastic ave is one of these
applications that relies on the
chainlink price feeds in order to
understand the ratio between how much
you have deposited as collateral and
then how much you can borrow and take
out if we look in our wallet now we can
see we still have some aethe
we also have some eath and now we have
zero die because everything's paid back
but we're still gaining interest on the
eth we have deposited
let's go ahead just reconnect
let's go ahead back to testnet.aver.com
and let's just withdraw all of our eth
now keep in mind when working with some
of this this is a test net right and
working the way we're working right now
is just on a test head so sometimes the
test net doesn't work quite as well as a
main net because it's just for testing
and doesn't have the exact same support
we were just working on the test net
but if you want to go to ave for real
you can go to
app.avefork.com connect your wallet on
the ethereum mainnet
connect your wallet
move to the ethereum maintenance and
interact with it exactly the way we just
saw now if we're on the maintenance here
we can see some additional pieces when
you deposit something like die
yes you get 2.3
back as interest paid to you for
depositing the die
you also get a little bit of what's
called a governance token you also get a
little bit of ave token i know it's
really small here but
this is an additional incentive that ave
has given the users for working with
their protocol since ave is a
decentralized protocol in order for
anything to be improved or anything to
be updated on the protocol it actually
has to go through a decentralized vote
so these governance tokens actually
dictate and decide how the protocol
improves moving forward now that we
understand how to work with all of that
through the ui
let's actually learn how to interact
with ave and interact with defy all from
our scripts learning how to do it this
way will get us one step closer to being
a quantitative defy engineer or d5
researcher this is someone who
programmatically does algorithmic trades
algorithmic modeling and just does
everything in a programmatic sense
making them much more efficient and
powerful interacting with d5 now all the
code that we're going to be working with
here is in this avi brownie pie
application and you can always refer
back to it in the link in the
description or in the link in the github
repository and see all the code written
yourself so with that create a new
folder and open up your vs code to that
folder and let's get into it and ave has
some fantastic documentation that we're
going to use as well link here is also
in the description let's go ahead and
start
with our our basic brownie setup just
with brownie init and we got a new
brownie project we got all of our
folders in here and we are good to go
now for working with browning we're
actually not going to really be
deploying any contracts because all the
contracts that we're going to work with
are already deployed on chain all of
them are just going to be working right
with ave here create a quick readme.md
so we can know what we're doing here
number one we're going to try to deposit
some eath into ave
then we're going to borrow
some acid
with the eth collateral
and then if you wanted to i challenge
you to actually sell
that borrowed acid
this is what's known as
short selling but we're not going to do
that here and then we're just going to
repay everything back
great and this will be the full
functionality of working with ave in
this deployed contract everything that
we're going to learn here will teach you
how to work with other
contracts as well such as paraswap or
unit swap
or any other type of swapping contract
that will allow us to buy and sell
so let's just go ahead and create a
script we'll call it ave
borrow that pie let's go ahead and
create a function called def main and
we'll just do
pass for now the first thing that we
need to figure out how to do is deposit
some f into ave
when we actually deposited our f via the
ui
you can actually see
when we call this deposit function if i
hit this deposit button here
oddly enough
if we go to this contract address
on the coven ether scan
we'll see
that this address is actually what's
called a west gateway
what ave is doing like i was saying
before and let's go ahead and actually
cancel this for now reject what ave is
actually doing here is swapping our
ethereum for west
again west is an erc20 version
of ethereum and this allows it to easily
work with all the other erc20s on the
obvi protocol like die usd coin
you know ample fourth link et cetera
so we actually have to do the that as
well
so the first thing we're going to need
to do
actually isn't deposit some of our eth
the first thing we're going to need to
do is going to swap our
eth for
west so let's even just put this in its
own little script we'll call it get
weth.pi so we're going to have a
function
def main
i'm just going to do pass for now but
we're actually going to want to use this
get wet function in our ave borrowed a
pi
so we're going to actually have a main
and we're going to have a def
get weth
and our main function is just going to
call
getwef so how do we actually
convert our ethereum to wef or wrapped
ether we'll even do a little dock string
here
mint's weth by depositing eth
now to save gas we could actually
interact with this weft gateway for ave
but i'm going to teach you guys how to
just get west in general so we can look
up the west contract
ether scan
the west coven contract ether scan
and we'll see here
we have this wrapped ether page
and we can go to the contract and we can
see that this is indeed verified
the way ath works is there's
a withdrawal and deposit
we deposit eth into this contract and it
transfers us some wealth
so this is the first contract that we
actually want to interact with so we
need our script to be able to call this
deposit contract
so
per usual the two things that we need to
do this are going to be an api
and an address
for this web contract i really like just
doing everything directly from the
interfaces i've already copy pasted the
interface
into this here so we're going to go to
interface dot sol and we're just going
to copy all this right here
so in our interfaces
we create a new file we're going to call
it iweth
dot soul
we're going to paste it in
you can see this has all the exact same
functions as our deposit contract
symbol name
transfer pretty much everything you'd
expect from erc20 plus this extra
deposit piece
we'll call this iweb it's a common
naming standard to just have i in the
name of what your contract is when
you're talking about an interface so we
have an interface now
and we also have
an address
but again this is our address on the
coven network since we know ahead of
time that we're probably going to be
using this on different networks like
mainnet and coven and etc we're actually
going to create a new file we're going
to add our brownie config
hopefully this is starting to look a
little familiar to you now
we're going to go ahead and add our
networks in here
in here we're going to go ahead and add
coven and in here we're going to write
west
token
and we're going to add
this address of the web token
paste it in here
while we're in here
we're going to add the rest of our
pieces we're going to add wallets
from key
private key
and that's all we really need for now
speaking of which we probably are still
going to want to test this locally
now since we've done some work with
testing we know that for testing
we can do our
integration test into
integration tests
on kovan because there's an integration
test there
what about our local tests
well this is something good that we're
thinking about right now we know that
ave actually has
all these same contracts on the main net
as well
and we also know that we're not going to
be working with any oracles because that
we don't actually have to deploy any
mocks ourselves we can if we want to but
we don't have to what we can do is for
our unit tests
we can actually just use
the mainnet fork network and just fork
everything that's on the mainnet into
our own local network so instead of
actually using mocs we'll basically just
mock the entire mainnet and one more
time just so that we absolutely have it
here if you're not working with oracle's
and you don't need to mock responses we
can just go ahead and use a mainnet fork
to run our unit tests if you are using
oracle then it makes a lot more sense to
do the development network where you can
mock oracles and mock oracle responses
with this in mind we know that we're
going to be doing a lot of our tests on
mainnet fork
we can go ahead and add a mainnet fork
network here and then we can just add
the mainnet web token
for mainnet fork so we'll look up web
token
etherscan
web token etherscan
and we'll grab this contract address
remember absolutely positively if you
want to double check that the contract
address that you're working with is
correct i highly recommend you do so
because if you get it wrong you could
accidentally add some money to a
contract address that you don't want
so we're going to have the mainnet fork
address b the web token address
and in our terminal
we can do brownie
networks list
and see that indeed we have a mainnet
fork here that's going to use the
ganache cli to fork mainnet for us
there's there's a link in the
description to refer back to the section
where we actually set this up so now
that we have the interface we know that
we can actually compile it down to the
abi so back in our get wet here
first thing we need to do to make any
transaction obviously is get an account
well
this is where we can go back and make
our helpful scripts
so we can go ahead
do def
get account
index equals none
id equals none
same as before
and if you have your get account
function from our last demo you can just
go ahead and copy paste it in here all
right great now we have our get account
function so we can do account now equals
get account
oh but we have to import it in here so
we'll do
from
scripts dot
helpful scripts
import
get account
and depending on your python version
we'll add in it that pi just so that
python recognizes that scripts is indeed
a module all right cool so we have our
account where we can make some
transactions with
now let's go ahead and get our wef
contract
to do this we can import interfaces from
routing
browning
import interface
same as we did before
and we can do with
equals interface
dot i with
and the address here is going to be from
our config
config
networks
dot show active
and then
web token
we also have to import config from
browning
and network as well
now you might be asking why aren't we
using the get contract function here
well you can absolutely 100 go ahead and
use that get contract function but since
we're going to be testing on mainnet
fork here i know that we're always going
to refer back to the config so i'm
confident that i'm not going to be
deploying any mocks
it's better practice to go ahead and use
that getcontract function but for this
one we'll just make it a little simpler
and use the config
and now in a fig if we're on the coven
network we're going to use this one
if we're on mainnet or maintenance fork
we're going to use this one
for going to mainnet or for to real
production you could also have a mainnet
network and it'll just be an exact copy
of the maintenance fork
and remember we're going to want our dot
env our env file
our environment variables to get pulled
from that dot env file so we can just
set it like this now everything in our
env file will get pulled in
automatically
great so we have an address and we have
an abi which comes from the interface
now we can just call we can just call
this deposit function where we deposit
ethereum and we get wef so now we'll
just do transaction equals wealth
dot deposit
and we'll do from
account
value
is going to be let's just say 0.1 so 0.1
times 10
raised to the 18.
so we'll deposit 0.1
and we should get 0.1 wef in return do a
printf string
received 0.1 weft
this doesn't even need to be printf
and then we'll just return tx
now per usual
if your environment variables aren't set
such as private key we're going to want
to do that so in our emb we do export
private key
equals 0x at the beginning right here
we're going to export web 3
infero
project id we'll want our ad our web3
inferior project id which we've got
before
if we want to use our etherscan token we
absolutely can
and since we're putting a whole bunch of
stuff into dot and v we want to make
sure in our git ignore we have
dot and v so we don't actually push this
up to github again if you're nervous
about having all these ambs in here you
can absolutely do the accounts.add or
whatever other methodology you like to
set your environment variables anyway
let's go ahead and run this script now
so we can do brownie run scripts
get wet pie
network
coven
generating the apis from our interface
we have a little transaction hash that
we can use
pop into the coven etherscan
and we can see
the transaction going through in our
wallets
we'll get minus 0.18 and we'll get plus
0.1 weth
so we can see it's actually been
successful
to add this and see this on our metamask
we're going to grab the contract address
here we're going to go back to metamask
add token paste it in here
add tokens and you can see we now have
0.1 with if you want to switch back your
weft to ethereum you would just hit this
withdraw function or
we could programmatically add a
withdrawal function in here this
withdrawal function will run for
ethereum withdrawal and take our
ethereum out of the contract and burn
the weapons replace it with weft so you
need to swap your weft back to get your
eth out awesome we have some weft and
now we have an erc20 token we have an
erc20 token that we can use to interact
with the ave application now that we've
got this get weth function let's go
ahead and start borrowing so let's go
ahead and start with our account
it's going to equal to get account
which now we're going to want to import
right at the top
like so
then we're going to get our west address
or we can even just do our erc20 address
because the web token is in erc20 and
maybe we want to deposit some other
erc20
we'll do config
networks
network dot show active
left token
and of course
we're going to have to now add from
brownie
import
network
and now we want to call this get weth
contract
just in case we don't already have wef
we would just add another from scripts
dot get weft
import
get west but we don't actually need to
call it right now because we already
have some wrapped ethereum in our
covenant address now if we want to test
this though on our local mainnet fork we
probably will want to call this getweft
so i'm just going to add a little if
if
network.showactive
is going to be our
mainnet fork
we should go ahead and call this get wet
function and for brownie we're also
going to want to import this config
we'll also have to add
mainnet fork
to our local blockchain environments
like so
so that when we call git account in our
scripts it actually knows that it's a
local environment that we're working
with and it will just return accounts
zero instead of us having to actually
load a private key in every single time
and we want to actually wait for our
transaction to complete here so we'll go
ahead and add this weight and then do
tx.weight
and wait for this transaction to
actually finish otherwise brownie will
get a little bit mad
so now that we have that we can run
brownie
run scripts
ave bar to pie
network
maintenance fork
so you can see that actually in this
case testing everything on mainnet fork
is going to give us a really really
accurate view of what doing this on
mainnet actually is going to give us we
don't have to do any mocking we can
literally just fork all of mainnet and
go from there we are still going to test
on kovan though in a little bit just so
we can see all the transactions that go
through how long it takes for stuff to
happen
so
now that we've gotten some wealth here
we actually need to go into our second
bit we're going to deposit some f or in
our case
some
wealth into ave so how do we actually do
that
well everything that we need is going to
be in this ave
documentation here
where we deposit and borrow from in ave
is in their contract this lending pool
you can see here the lending pool
contract is the main contract for the
protocol it exposes the user-oriented
actions that can be invoked in solidity
and web-three libraries and these have
all of the functions that we need it has
deposit where we deposit our asset as a
collateral withdraw where we take it
back we have borrow we have repay
and we can have we have swap borrow
rates
and a couple other interesting ones
which we'll go into later but for now we
just really need to focus on repaying
borrowing
withdrawing and depositing
so as you probably guessed deposit is
the function that we're going to work on
right now
and since this is the contract that
we're going to work with as always the
two things you need when working with a
contract are going to be the abi and the
address so we're going to get this
lending pool contract we're going to say
lending pool
equals and we're actually going to even
make a function called get
lending pool
so down below we're going to do def
get lending pool
lending pool not poll
and we're going to get the lending pool
address and the lending pool contract so
we can interact with it down here now
something about this lending pool is
that the lending pool address can
actually change a little bit depending
on a lot of different pieces
so there's actually this address
provider which gives us the address of a
specific or particular market if we go
back to this ave ui there's actually
different markets so there's different
types of ways we can interact with ave
we're just going to work with the basic
ave v2 because it's easily the most used
on mainnet as well the address provider
registry will give us so this address
provider will give us the address of the
lending pool for our market if we want
to go across different markets we'll
have to go to the address provider
registry to find it but the addresses in
here don't change and the addresses in
here don't change it's just the lending
pool address itself might change so we
just have to go to
this address provider here and there's
just one function that we need to work
with it's this get lending pool which
will give us the address of the actual
lending pool so don't let this confuse
you too much basically all we're trying
to do is we're saying hey where is ave
located right now and ave has a contract
that will always tell us where the main
ave contracts are and that's this
addresses provider right here so this is
another contract that we have to work
with and again when we have a contract
what do we need we need an api
and we need an address so we can
absolutely once again we could go ahead
and
you know copy paste like abi equals
whatever the abi is but we're just going
to use an interface because because life
is great with an interface
so a couple of great things about
interfaces too if we know we're only
going to work with one or two functions
we can actually just make the interfaces
ourself
so an interface we could do a new file
we could do i
lending pool
address provider that's sol
and we can just add it in here ourselves
so we'll first do sp dx
license
identifier
and we'll do like mit or something
we'll do pragma
solidity
0.6.6 or whatever we want to do
and then we'll do interface
i
landing pool
addresses pro
divider
excuse me this should be a lending pool
address says
provider
and we know that there's only one
function
called get
lending pool
and we're not exactly sure what
getlendingpool is defined as but what we
can do
is we can go to
ether scan eat the scan ave
lending pool addresses
you can see here this is actually the
lending pool
but what we can look at is the ave
protocol we can go right to the github
we can go to contracts
we can see they have an interfaces
section
and they have
this lending pool addresses provider
get lending pool and kind of as we
expected it's an external view and it
returns an address so we can literally
just copy paste this
into here
and we could run with this and this
would work perfectly fine
but this leads us to the next point we
might as well just grab the whole thing
this way we know for a fact we're not
getting anything wrong but yes if we
wanted to
our interface could be this
right because this is going to compile
it could be this
because this interface is going to
compile down to an abi and the abi is
going to say hey there's a function here
and that's all the abi is really doing
it's just telling us how we can interact
with a contract but let's just go ahead
and add everything so that if we want to
interact with more things we can so now
we have the api we also now need an
address which we can definitely find
from the ave documentation we can go to
their deployed contract section we find
lending pool
addresses provider which is going to be
right here
we're going to copy that
and where are we going to put this well
as you know we're going to put this in
our brownie config we're going to do
lending
pool
addresses
provider
i'm going to paste that right there and
since we know we're also going to do
coven
we can also grab from kovin here
so lending pool addresses provider
we're going to copy this here
and do
and we're going to add this addresses
provider for coven as well
boom now we have it for both coven and
for maintenance fork
awesome
so we can keep going now now that we
have an avi and we have an address for
both coven and for our mainnet
maintenance fork
what we can do now
is we first get the lending pool
addresses provider
it's going to be
from our interface which again
we're going to grab from brownie
interface dot i
lending pool
addresses provider
which the address of that is going to be
config
networks
network.showactive
lending
pool
addresses provider
and then we're just going to say
lending pool
address
it's going to be equal to
blending pool
i'm just going to copy and paste instead
of typing the whole thing address
divider provider dot get
lending pool
right because again
this address provider has this get
lending pool which returns this address
which is the address of the lending pool
then now that we have this address we
can actually return the lending pool
contract
by once again getting the api
and the address
of the actual landing pool so we have
the address
check
we just now need the api which once
again we can work with our wonderful
interfaces here do new file
i
lending pool
and there's only going to be a couple of
functions we're going to work with here
but ave actually gives us the interface
right here
and
ave actually even gives us the interface
of the lending pool address provider for
us so we can go ahead and copy this pop
it over into here now we do need to
actually change one thing in here as
well this interface imports locally with
this dot slash so we actually just need
to change these imports to actually
import directly from github instead of
importing locally
luckily this is something we already
know how to do so let's go to our
brownie config
and up at the top we're going to add
this dependencies bit in pen
then c's
so we're just going to work with ave's
protocol right from github
so
we're going to work with ave slash pro
tow call
v2
and let's see what their latest version
is
looks like they got a couple different
versions here
1.0.1
so let's go ahead and work with this one
at
1.0.1
and then with compiler
sulk
remappings
per usual
we're going to say at
ave
is going to be equal to this dependency
this way brownie will download this
right from github and now we can just
use this at ave
instead
so back in our eye lending pool.sol we
can just change this
to poll right from github and if we look
in github
we go to their contracts section
we go to their interfaces section
by lending pool
we know that we can pull this from
at ave
slash contracts
slash interfaces
because we see this eye lending pool
addresses provider
right in here
and then this data types bit
you can actually look in contracts
and this i know because i've i've been
through already it's in protocol
libraries
types
and here it is datatype.sol so we can
just take this exact path again
and do at ave
contracts
slash protocol
slash libraries slash types
data type dot sol okay great so now that
we've actually imported this interface
for us to use we can go ahead and
compile just to make sure that
everything is working correctly brownie
compile
and perfect if these interfaces had an
issue they actually wouldn't compile
through brownie here so we know that
they're compiling correctly but great so
now that we have an interface we know
that these interfaces compile down to
the abi
and we already have the address here so
to actually interact with the lending
pool now we can just do
lending pool
equals
interface
dot i
lending pool
and we'll add this lending pool address
blending pool and then we can return
lending pool so now we have a function
that goes through the lending pool
addresses provider from the ave
documentation and returns this lending
pool contract that we can now interact
with and we can even test this out by
just printing this landing pal address
in our script
so we'll do brownie
run
scripts
ave borrow network
mainnet fork
and perfect we we can see the address
here is printed out and there are no
errors so we know we're doing it right
so now that we have the actual address
what we're going to do now is we're
going to take this wrapped aetherium
that we've got this erc20 version of
ethereum and we're going to deposit it
into this contract just like what we did
in the user interface in order to
actually first deposit it we need to
approve this erc20 token erc20 tokens
have an approved function that makes
sure that whenever we send a token to
somebody or whenever a token calls a
function that uses our tokens we
actually have given them permission to
do so so that's the first thing that
we're going to actually have to do
is we're going to have to approve
[Music]
sending our erc20 tokens
and this resembles so since i know that
we're going to have to approve a lot i'm
actually just going to go ahead and make
an approve
erc20 token function similar as to what
we did with the get lending pool
so we're going to need to approve this
erc 20 so we're going to need to approve
this erc20 so let's go ahead and make a
function we'll call it def
approve
erc20 so how do we actually call this a
prove function on a token contract
well
as always we're going to need the abi
and the address of the token contract
same as always i told you i was going to
be saying this a lot now we could create
our interface ourself looking at all the
functionalities of the erc20 tokens so
we could go to eip20 look at the token
standard find all the different
functions and put them into our
interface
or we can go ahead and just cheat and
just grab it from my github repository
here
so i already have an ierc20.soul right
here
and we're just going to copy everything
in here and
add it in a new file called i yourc20
that's sold
and paste it in here so you can see
there are a number of different
functions in here
we can check the allowance we can check
the balance of different addresses
how many decimals a token has the name
the symbol we can do some transfers and
transfer from and then the function that
we're going to be using is this approve
function so right here we can already
see
the parameters this approved function
takes
we're going to need to have a spender of
who to approve can spend our tokens and
then how much they can actually spend so
if we come back over to approve erc20
we know that for input parameters we're
probably going to need an amount
a spender
address
the erc20 token address
so which token we're actually allowing
to spend
and then an account right or this is
going to be that from
account bit so we'll just have this be
passed as part of the function
parameters so let's go ahead and code
this let's first just do a quick print
line
so that people know what this
transaction is doing we'll say approving
prc20
token
and then we'll get the erc20 token by
saying e or c equals interface
same as always dot i e or c 20
and then we'll give it
whatever erc20 address that we pass to
this function
and now we can actually interact with
this contract and we can call that
approve function
so we'll say transaction
tx or again tx usually stands for
transaction
equals erc20
dot approve and we're going to approve
this spender
for
an amount
and then we'll say from
account we'll do tx.wait we'll wait one
block confirmation for it to finish
and then once it's done
we'll do print
approved and we'll return the
transaction
awesome so now we have an approved erc20
function that we can use to approve any
erc20 token so back up in our main
function we can run approve vrc20 for
some amount which right now we don't
have defined
the spender is going to be this lending
pool but the address of the lending pool
because remember lending pool is the
entire contract we just want the address
the erc20 address of course is going to
be the erc20 address and the account of
course is going to be our account
the only thing we don't have to find
right now is some amount which we can
make it really whatever we want to be to
keep things standard let's just go ahead
and do 0.1 so i'm going to make this a
global variable i'm going to say amount
equals
one
one two three four five six seven eight
nine ten one two three four five six
seven and we can go ahead and do
amount
we're gonna of course doing all these
zeros is from incredibly disgusting so
we're just gonna refactor to do from web
33 import web and then instead of always
and we'll just do web three three
two two
0.1 0.1 which is the amount that we
actually want and we'll say either
now we can run browning
run scripts ave borrowed a pie
network main net fork
and we can go ahead and see that our
approval function is working as intended
network that will always be doing this
fine
any type of
we can do so let's go foreign and change
our default network to mainnet for
mainnet so we don't have any network in
our browning let's go back to our ave
borrowing section now so we have
everything approved
now we just need to go ahead and deposit
it into ave
since we know we're probably going to
use this a lot too let's go ahead and
create a
deposit function since we have
everything approved we can now go ahead
and use the lending pool deposit method
and we can check the documentation here
or look on github or etherscan to see
what the parameters that it takes are so
i'm even just going to go ahead
and copy all this
bring it over here
so what we can do now
is we do lending pool
dot deposit
and then all these parameters let's go
ahead and walk through them one by one
so first thing is going to be the
address of the asset which we know
is going to be your erc20 address
boom
the amount
of the token which we can go ahead with
our amount variable
address on behalf of is just going to be
our account.address we're depositing
this collateral for ourselves
and then referral code so referral code
is so the referral code is actually
deprecated and workloads don't actually
work anymore so we're just always going
to pass 0 here and just to make sure we
know that this is what we're doing we're
going to go ahead and print
depositing
one two three
and then after we're done we're gonna do
print
the ted
and whoops looks like we forgot to add
that final dictionary here
of from
accounts
ah one more thing here let's go ahead
and do tx for transaction
equals lendingpool.deposit and we're
going to go ahead and once again we're
going to wait for one block confirmation
wait
one
transactions still being processed so
now if we run brownie run scripts ave
borrowed up high
we can see that this actually went
through fine
all right now that we have some
collateral deposited we can go ahead and
actually take out a borrow we can go
ahead and borrow some other asset the
question is going to be how much how
much can we actually borrow how much
should we borrow
what would result in a positive health
factor well maybe we should actually
pull off chain some of our stats how
much do we actually have deposited
how much collateral we have how much
debt we have and so on and so forth that
way in the future when we don't start
clean we can take some inventory of
where we stand with our collateral in
our debts at the ave documentation
we can go ahead and see this this
function called get user account data
this is going to return the user account
data across all reserves so it's going
to get the total collateral that we've
deposited in terms of ethereum it's
going to get our total debt in terms of
ethereum how much we can borrow the
borrowing power that we have the
liquidation threshold or how close to
that liquidation threshold will be the
loan to value ratio and again this
health factor this health factor is
obviously incredibly important because
if it drops below one or reaches one
users can call this liquidation call now
this function returns all these
variables but for now we really only
care about how much collateral we have
how much debt we have and how much we're
available to borrow so let's go ahead
and write a function that will actually
sort that out for us we'll call it get
borrowable
data
borrow a bull
data so let's go ahead and create this
def
get borrowable
data
and we're going to pass in the lending
pool as a first parameter and then the
account as the second parameter because
we're looking to call this function on
the lending pool from an account so
let's go ahead and just call that
function so we'll do lending pool
dot get user account
data
and we'll pass in account that address
because we look at the api again
all that it needs is a user's address to
get started here
and it returns one two three four five
six
variables so we can go ahead
and get all of them
with this tuple syntax here so we'll say
total
collateral eath
total debt eath
available
borrow eth
current
liquidation
loan to value
and then the health factor
so it's with this syntax here that we
can actually get all of these variables
with this one call and again this get
user account data is a view function so
we don't need to spend any gas all of
these variables are going to return in
terms of way so let's just go ahead and
convert these from whey to something
that makes a little bit more sense to us
so we want to get this available borrow
each so we can figure out how much we
can borrow let's get that
in terms
that we can actually understand so we'll
do fromway
available borrow eth in terms of ether
we'll do total
collateral eth equals web3
that from way
and we'll do total collateral eth
ether
ether
and then we'll do total
debt eth
equals same thing web3 dot from way
total debt eth
terms of ether
and let's even do a little printf
statement for each one of these so we'll
do print
f
this f allows us to put variables inside
the print function and we'll say
you have
total collateral eath
worth
of eath deposit 10.
we'll even copy paste that a couple
times and we'll change this one to
total debt eath
and we'll change this one to
available borrow eth
so we'll say you have
worth of ease deposited
you have total death eat worth of
f borrowed
and you can borrow
available borreeth worth of eath
and then we're going to go ahead and
return
again we're going to use this tuple
syntax so we can return two variables
and we're going to say a float
of this available borrow eth
and a float
of the total debt eth
the reason that we have to add this
float variable here is that without it
some of the math that we're going to try
to do later won't pan out as well so now
we have this function get borrowable
data we're going to pass the lending
pool
and we're going to pass our account here
since we're returning
the borrowable eth and the total debt we
can say borrowable
eath and then total
debt
equals that function right there so
let's go ahead and try this out
with
running run scripts ave borrowed a phi
pi
again
because in our config
we have a default network of mainnet
fork
things seem to be approving things seem
to be depositing and awesome
we have we have our output here we
deposited 0.1 worth of f we have 0 f
borrowed and we can borrow 0.8 worth of
f yes this is correct even though
we have 0.1 f deposited
we can only borrow
0.08 this is because the liquidation
thresholds of different assets are
different in this risk parameters
documentation here we can see
the different liquidation thresholds on
the different assets we can see that
ethereum has an 80
loan to value so with ethereum we can
only borrow up to 80 percent of the
deposit assets that we have
and
if we have more than 82.5 percent
borrowed will actually get liquidated it
also tells about the liquidation bonus
reserve factor and some other helpful
pieces in here as well but now that we
have this borrowable ether mount we can
go ahead and actually borrow some dye so
let's do a quick print saying
let's borrow now in order for us to
borrow some dye we also need to get the
conversion rate
we need to get die in terms of f so
we're going to have to use some price
feed here luckily we already know how to
work with chain link and how to get
price feeds ave uses the chain-link
price feeds as well so we're using the
exact same conversion rate tools that
avi is going to use so let's go ahead
and create a function to get us this
conversion rate we'll say the die to f
price
is equal to get
asset price and then here we'll pass the
die
f
price feed
this will be the address of the die
ethereum conversion rate let's go ahead
and create this function call it def
get
asset price
and the parameter needs is going to be
price feed address so the first thing
that we're going to need is we're going
to need to get this die f price feed
where can we get this
well as we know per usual we'll head
over to the chain link documentation
we'll go to ethereum price feeds we'll
find done
and we'll paste it into our config for
mainnet so we can go ahead and add the
die
f
price feed
in here and paste it into our config
again if we want to test the coven we
can obviously just scroll down
look for coven
find the dieth right here
grab that address
pop it in for coven
and then we can get this the same way
that we got the address of the web token
so i'm just going to go ahead and copy
this
paste it here but instead of having weft
token in here
we'll do die
f
price feed
and now we have a way to change the
price feed address depending on what
network we're on so in our get asset
price function we're going to do the
same exact thing that we always do we're
going to grab an api
and an address
to work with the contract so again we
can get the abi by just working directly
with the interface
so we'll say die
f
price feed
equals interface
dot
aggregator
v3 interface because this is the name of
the price feed interface
which again if we look in our interfaces
it looks like we don't actually have so
what we can do
is we can go to the chain like github or
as you guys are already starting to
figure out all my example code has all
these interfaces as well but we can go
right to the source too
what we can do we go here we go to
contracts
we're going to add source
we'll do
0.6 we'll do interfaces and right here
is the aggregator v3 interface so if we
want we can just copy this whole thing
move back over to our interfaces
new file and this file is actually named
aggregator v3 interface you could call
it eye aggregator v3 or aggregator v3
interface you could keep it with i
aggregate or v3 outsole to keep with the
convention that we have
or you can just call it aggregator
v3 interface dot sol
to keep in line with what the chain link
code is actually called them i'm going
to call mine aggravated v3 interface
you'll notice a couple different
projects have a couple different
conventions but now that we have it
saved we can do interface the aggregator
v3 interface and we'll pass it this
price feed address now this diet price
feed is going to be a contract that we
can call a function on again we can
always refer back to the get the latest
price documentation to see how to
actually work with it there's even some
python code here for working with it in
web 3. we're going to go ahead and call
this latest round data function which we
can also find in our aggregator v3
interface this latest round data
which returns a round id
answer started at ended at and answered
it around
all we're really concerned with is this
answer bit here so the way we can do
this is we can say latest price equals
die dieth price feed the latest
round data and instead of grabbing
all five of these one two three four
five
what we can do is we can actually just
grab
the price which is at the one index so
round id is at zero price is at one
started it's two et cetera
so we can just say
at the first index and then we can
return
a float
of
this latest price
we can even print
another printf statement
the die
f
price is
latest price
so let's go ahead and run this
and great we have the die f price video
which of course we know that looking at
this right now this isn't in the right
units we know the diet price feed has 18
decimal places so what we can do then is
we know that this number would be one
two three four five six seven eight nine
ten one two three four five
six seven eight
this number is really zero point zero
zero zero four blah blah blah blah blah
so maybe we don't want to return it like
so maybe we want to say the diet price
feed is and we add
a little bit of web3.pi to make this
make a little bit more sense so we'll
say web3
dot from
way
and we'll add this latest price bit in
here comma
ether
maybe we'll even do a converted
latest price which is going to be equal
to
web3 dot from way
latest price
ether
and we'll print that out instead
so let's go ahead and run this again
all right that looks a little bit more
accurate perfect
okay great now we have the die eat price
we're getting really close to being able
to borrow this actual asset and let's
even return this converted lated price
here just so that we're always working
in units that we understand
okay now we're getting somewhere now we
can calculate the amount of dye that we
want to borrow we can find this by doing
a little bit of math we're going to do
the reciprocal of the die eat price
times
our borrowable eath and just to be safe
we're going to times it by 0.95
so this line we're converting our
borrowable each
to
borrowable
die and then we're timing it by
95 percent we're timing it by 95 because
we don't want to get liquidated so we're
going to be a little bit more cautious
remember how we slid that sliding scale
around to make it safer and less safe
well the lower percentage that we
actually borrow maybe we even borrow 50
of our collateral the safer that we're
going to be so keep that in mind when
you're deciding how much to actually
borrow if you want to run this in a
production environment so now that we
have this amount data borrow let's even
print it out let's say print
f
we
are going to borrow
amount down to borrow
die and then
we're finally going to do it
now we will borrow
looking at the ave documentation we can
look at their borrow function and we can
see the api here let's go ahead let's go
ahead and call this function so we'll do
borrow transaction it's going to be
equal to
lendingpool.borrow
let's look at those parameters so the
asset that we want to borrow die address
so first we should get a die address
which we can once again we'll want to
put in our config
so we'll go over to our config
and we'll add
a die address or a die token here which
we can find on etherscan
token it looks like this is the token
right here so we'll copy this address
for mainnet remember if you want to run
this on coven you're also going to need
to have a die token for coven now on
test nets avi actually changes up where
the tokens for its test nets are
actually going to be so if we go to
their documentation we go to deployed
contracts
and we go to coven here you'll always
see this little flag thing pop up say
always ensure using the latest lending
pool address since coven is updated from
time to time it's going to be the same
thing if we scroll down for tokens they
have an up-to-date list of coven
addresses in a json file here so it
looks kind of gross but if we look up
die
we can see symbol die and the address of
die on the coven test net so sometimes
this does change so if you run into an
issue maybe it's because the die token
that you were working with on their
coventestnet has actually changed then
we're going to do config networks
network dot show active
diet token great now let's move on to
the next parameter
the amount which we just figured out
here
amount diet to borrow
which we do need to change back to whey
so we're going to do web3.2a
mount dye to borrow
ether
because right now amount down to borrow
is in our human readable version which
we need it in way
then our interest rate mode which is
going to be stable or variable stable is
where the interest rate will always be
exactly the same
variable will change depending on a lot
of different things going on with ave
for safety we're just going to go ahead
and add one here
then we're going to do a referral code
and on behalf of so referral codes no
longer exist so we'll leave zero it's
going to be on behalf of our self
so we'll do a countdown address
and then of course we have to do a from
account
then we'll wait for this transaction to
complete
and if we've done this right we should
have borrowed some dye programmatically
from the ave protocol so let's even
print
borrowed some die
and we can once again call our get
borrowable data function
since this get borrowable data function
will print out our new account
information for how much we borrowed so
let's go ahead and run this on mainnet
fork again
awesome so if we've done this correctly
we now see that we've borrowed some die
so we can see here we now have 0.1 worth
of f deposited
0.059999 worth of f borrowed
and we can borrow a little bit more
worth of f
this
0.75999 is actually
the die that we've borrowed so we've
deposited some eath and we've borrowed
some dye and obvious telling us how much
that dye converted to eat is there so we
actually borrowed 160 die
which is great all right we've now
learned how to borrow everything which
is fantastic let's go ahead and actually
repay that back so we're going to call
their repay function and let's just put
this into its own function called repay
all and we'll give it the amount that we
want to repay
the lending pool address and our account
so let's call
let's define
repay all or we're just going to repay
everything that we have
again we're going to add an amount
lending pool
and account
for parameters
so if we're going to pay back this
network first thing that we need to do
is actually call the approve function
i'm going to prove that we're going to
pay back so the first thing we're going
to have to do per usual is we're going
to actually have to approve that erc20
so
let's say how much
we're going to approve
web 3.2 way
amount
ether to the lending pool
and we'll grab it from the config
networks
network dot show active
and this is going to be the
die token again
and of course
with our account i believe our proof
erc20 already calls weight so we don't
have to call it here so once we approve
we're going to be using this die that we
borrowed to pay most of what we have
borrowed back now we're going to call
the repay function so we'll say repay tx
equals
lendingpool.repay
first we need the asset
that we're going to use to repay which
we're going to use config
networks
network dot show active
diet token the amount which is going to
be passed in here amount
the rate mode
which
we've hard coded to one
and the address on behalf of which is
going to be account
dot address
and then of course we always have to do
from account
then we're going to do repay tx
dot wait
we're going to wait one block
confirmation
and then we'll print
repaid
and if we've done all this right we'll
do one more print line saying
you just deposited
borrowed
and repaid
with ave
brownie
and chain link
all right moment of truth
let's see if this works
we did it repaid you just deposited
borrowed and repaid with ave brownie and
chain link awesome work now if you want
to what we can also do is we can see if
this will work
with our wallet address here so what i
can do is i can copy my address
go to coven ether scan
and paste it in here
and right now we can see
that i have a whole bunch of link and
some ether
what i can do
is actually test everything that we just
ran through on the cove intestine and
see
everything happen
right on this ether scan address so if
we've been following along correctly and
we've added contract addresses
appropriately
we should be able to run the exact same
script on the coven test net i'm going
to do one additional thing here though
i'm going to have us not repay so we can
see
us with a little bit of debt
so let's go ahead and run brownie
run scripts
ave bar to pie and we'll change to
network coven
and now it's going to take a lot longer
as we've seen before because we're
actually
making these transactions on a real
network whoops it looks like i got one
of the die f price feeds wrong for coven
so i can once again just go over to the
documentation
die
s
it looks like this is the real address
for coven
so we'll copy that
paste it in here whoops we should also
probably have some wet token so first
let's go ahead and run
our get wet script for coven
and we're going to change this account
to get account brownie
run scripts
from our helpful scripts that way we can
actually
that way we can actually use our wallets
correctly all right great so now we have
0.1 weft
and actually
again what we can do
is grab
this address here
add token paste it in
add tokens for the web token and now we
can see we have 0.1 with which is
perfect
so now that we have some width we can
run the borrow script ave
brownie run
scripts ave borrow
network coven
and wow we can see that everything went
through correctly and successfully
so since i actually commented out this
repay function we still should have die
in our address here in our wallet here
and again we can see that
by going to our brownie config
grabbing this dye token address
add token custom tokens next
ad tokens and we can see we do indeed
have 160 die in our wallet
we have no weft since it'll be in ave
now and we have borrowed die instead you
can also see that we now have this a
weft if we added it from when we were
working with the ui
we have this interest bearing with
instead of regular wrapped ethereum
let's look at one of these transactions
we can see
that our borrowed transaction
gave us some stable debt bearing dye and
also some dye so we owe ave some die
from this debt we got some debt we got
some dye and we gave out some ave
interest bearing dye to the rest of the
albe protocol you'll notice now if we go
to test.ava.com dash dashboard we'll see
exactly what our script just did we have
160 borrowed
and we have 0.1 eth deposited if we want
to repay
our funds we can do it
with our current collateral or from our
wallet balance
and you'll notice something if i try to
repay
everything from my wallet all the diet
that i've actually borrowed you'll
notice we don't have enough funds to
repay the full amount
this is because since we actually
borrowed a little bit we've include some
of that interest so we actually owe more
back than we originally borrowed that's
how the loans work so when you're
designing this repay functions be sure
to have that in mind you can also have
your repay be -1 to repay the entire
debt it's recommended to send an amount
slightly higher than the current amount
borrowed but in any case maybe we say we
want to do from our
current wallet we'll hit max but maybe
we want to actually just repay with our
current collateral we can go ahead and
repay the maximum amount again we could
do this all from the ui
we'll approve and this is exactly what
our repay function actually did and now
we're all repaid up if we go back to our
dashboard and we hit refresh we'll see
we just have a tiny bit of ethereum and
no more borrowed assets awesome you've
essentially learned everything that we
need to go through for here
this is a massive step forward in
teaching you how to become
quantitative defy wizards and build
really robust applications and really
robust financial applications in the
default world now something i want to
point out even though this isn't a
python course and we're teaching more
about solidity and smart contracts it's
still in your best interest to test
these functions
yes i know they're python functions but
it's still going to be in your best
interest to test them to make sure your
application always works as you expect
it to now i'm not going to go through
this testing suite that i put here but
it's a really simple testing suite to
test some of the different functions
that we created
it can be really helpful especially for
something like get asset price where the
math might be a little bit off and you
want to make sure it's correctly again
link in the description to seeing some
of these tests
this is actually going to be even easier
than that lottery contract that we did
since we're just testing python
functions
and again you can test these all with
brownie test
all right you are all doing
fantastically now is another fantastic
time to take a break go for a walk get
some food because our next session our
next lesson we're going to be learning
about nfts how to build them use them
and deploy them
look nfts are hot right now nfts also
known as
erc721s are a token standard that was
created on the ethereum platform nft
stands for non-fungible token and is a
token standard similar to the erc20
again erc20s like link ave maker all
those goodies that are found on the
ethereum chain an nft or a non-fungible
token is a token that is
non-fungible this means that they are
starkly unique from each other and one
token isn't interchangeable with any
other token of its class a good way to
think about it is one dollar is
interchangeable with any other dollar
one dollar is going to have the same
value of another dollar those are
fungible tokens that's like erc 20s one
link is always going to be equivalent to
one other link by contrast is going to
be nfts those you nerds out there would
know like a pokemon would be a good
example of an nft your one pokemon is
going to have different stats different
move sets and isn't interchangeable with
any other pokemon or maybe a more
relatable one is like a trading card a
unique piece of art or the like so
that's what these nfts are they are
non-fungible non-interchangeable tokens
that for the moment are best represented
or thought about as digital pieces of
art that are incorruptable and have a
permanent history of who's owned them
who's deployed them etc now like i said
nfts are just a token standard so you
can actually make them do much more than
just be art you can give them stats you
can make them battle you can do really
unique things with them you can do
pretty much whatever you want with them
but right now the easiest way to think
about it and the most popular way to
think about it is by calling them art
it's odd or some type of collectible or
just anything that's unique now they've
been getting a ton of buzz recently
because we've been seeing more and more
of these being sold at insane prices
like we saw axe infiniti sell nine plots
of their land nine plots of their unique
land for 1.5 million dollars we also saw
the original creator of the neon cat you
know this cap
sold for like 300 eth so like i said
they're just tokens that are deployed on
a smart contract platform and you can
view them on different nft platforms
like openc or wearable and these are the
nft marketplaces that let people buy and
sell them you obviously can do that
without these marketplaces because it's
a decentralized but they help and give a
good user interface so that's the basic
gist of it let's talk some more about
the standards the erc721 standard or the
nft standard this is the basis of it all
there is another standard that's
semi-fungible tokens the 1155 we're not
going to talk about that here but you
can check it out the main differences
between a 721 and an erc20 on erc20s
they have a really simple mapping
between an address and how much that
address holds 721s have unique token ids
each token id has a unique owner and in
addition they have what's called a token
uri which we'll talk about in a minute
each token is unique each token id
represents a unique asset so since these
assets are unique and we want to be able
to visualize them and show what they
actually look like we need to define
those attributes of the object if it's a
piece of r we need a way to define what
that art looks like if it's some type of
character in game we need a way to
define that character's stats in the nft
this is where metadata and token uris
come in so if you know anything about
ethereum you know that sometimes gas
prices get pretty high especially when
it comes to storing a lot of space it
can get really really expensive so one
of your first questions might be well
are they storing these images and and
these are pieces on chain and the answer
is sometimes back when they were coming
up with nfts and artists were deploying
stuff the eth devs and the artists were
like yeah art let's do that art i'm just
going to deploy this one megabyte image
onto the ethereum chain and oh god it's
so much a gas expensive how do i
totally find it
i don't know why it's not um it's not
delivered and they realize that if they
put all this art on chain it's gonna be
incredibly expensive so to get around
this what they did is they put in the
standard what's called the token uri
this is a universally unique indicator
of what that asset or what that token
looks like and what the attributes of
that token are and you can use something
like a centralized api or ipfs to
actually get that token uri typical
token uri has to return something in
this format like this it has the name
the image location the description and
then any attributes below now if you're
like me your first question would
probably be we paul from a single
source
seems pretty
centralized
this is a current limitation of the end
of the ecosystem there is often this
talk of on-chain metadata versus
off-chain metadata because it is so much
easier and cheaper to store all your
metadata off-chain a lot of people will
use something like ipfs that is
decentralized but does take a little bit
of centrality to keep persisting but
they can also use their own centralized
api however obviously if that goes down
then you lose your image you lose
everything associated with your nft
because of this most nft marketplaces
actually can't and won't read off
on-chain attributes or on-chain metadata
because they're so used to looking for
the token uri obviously if you do
off-chain metadata you can't do anything
really cool or really interesting or
have any games with your nfts for
example if you wanted to create an
on-chain pokemon game all your
attributes would need to be on chain in
order for your pokemon to interact with
each other because if it was off chain
then that becomes a lot harder to
cryptographically prove so if you're new
with nfts and you're like wait this is
kind of a lot of information i'll make
it easy for you if you're looking to
render an image of an nft add your image
to ipfs add a metadata file pointing to
that image file on ipfs and then grab
that token uri and put it and set it as
your nft the chain link dnd article does
a great job of walking you through this
and showing you how to do this so be
sure to read that if you're looking to
learn how to do that so all the code
that we're going to be working with is
actually available for you in this
nft mix brownie mix it's an official
brownie mix and it allows us to deploy
these three adorably cute dogs
and there are two different types of
contracts that we're going to be working
with we're going to be first working
with a simple collectible and then we're
going to work with an advanced collect
the simple collectible is going to be a
very simple erc721 standard we're not
going to really add any bells and
whistles other than give it like a name
and then our advanced collectible is
going to take advantage of some of those
more advanced true scarcity features
that we were talking about so protocols
like avagochi and ethercards use
chainlink vrf to get verifiably random
numbers to create verifiably scarce nfts
something that's important to keep in
mind is that in the real world when
companies create trading cards there's
no way to prove how scarce or how
valuable these trading cards actually
are if we use a verifiable random number
then whoever is deploying these nfts
can't even control how rare these nfts
really are so we get this verifiable
scarcity and this verifiable rarity
which adds some value to the tokens if
you want to just go ahead and work right
from the brownie mix you can actually
just run brownie bake nft mix
and then cd into nft
and all of our code
is gonna be right in here we're gonna go
through and deploy and develop
everything from scratch because we're
going to actually take some previous
concepts that we've learned improve on
them and we're going to learn a lot of
nitty gritty interesting pieces about
making this hybrid smart contract
because these nfts really are a perfect
example of a hybrid smart contract they
have some off-chain component
interaction with a random number and
restoring their metadata with ipfs and
i'll explain ipfs a little bit more in
depth as we go on here
so let's go ahead and get to it i'm
going to go ahead and make a new
directory
called nft demo
i'm gonna cd into it
code
period
and perfect i have a blank project here
and you already know what the first step
we're gonna do is
is do brownie init to create our blank
brownie repository now let's go ahead
and create our first
contract we'll call this
simple
collectible
dot soul since this is going to be it
since this is going to be a simple
collectible a simple nft that we're
going to get started with now similar to
the erc20 this erc 721 standard
has a number of functions that we can
actually work with we can go ahead and
even look at the 721 the erc721
non-fungible token standard on the
eips.ethereum.org website and we can see
a sample interface and some sample
events and some functions and kind of
everything that we've grown to know and
love and once again instead of us kind
of recoding copy pasting all this from
scratch we're going to be using we're
going to be using open zeppelin's erc721
documentation for this
now we're going to be working with
version 3.x there is a version 4.x that
has come out using version 3.x of their
open zeppelin contracts is also i think
a little bit easier to explain but again
those who want to challenge yourself
definitely try their 4.x version so
let's go ahead and jump right into it
first we'll do our srspdx
license identifier
mit
then we'll choose our solidity version
we're going to use pragma solidity 0.6.6
but again most of this should work for
0.8 moving forward
and then we're going to go ahead and
look at the open zeppelin erc721
documentation
and we're going to go ahead and
grab this line right here
import open zeppelin slash contracts
token
erc721
erc21.soul you can even see
a sample erc721 that they give you and
this is actually going to be similar to
the erc721 that we're going to make so
we're going to go ahead and paste that
and of course since we're doing this at
opensupplement contracts we're going to
need to
create our brownie config
and same as always the pen
[Music]
then sees
it's going to be
open zeppelin slash open
zeppelin contracts
and again like i said we're versing
we're using version three
so
3.4.0 again and then we'll do compiler
sulk
remappings
and we'll say
at open
zeppelin
equals
this
and great let's even try to just compile
this right now browning compile
and perfect it has been compiled now
similarly to our erc 20 that we did with
open zeppelin we're going to do the same
startup here so we're going to say
contract
simple collectible is erc erc721
and this is how we're going to inherit
all of those functions
in the erc721 token standard here and we
can start adding r
and we can start coding our simple erc
721 now for our erc 721 we're going to
make it be a couple of these cute
adorable dogs so it's going to be one of
these three dogs for our simple
collectible we're just going to go ahead
and use the pug here so so you can use
any image that you want for this demo um
however if you want to just follow along
with us
we can just download this
dog and we'll call it pug create a new
folder
here called img and then i'm just going
to add pug.png to this img folder so
this is going to be the mft that we're
going to deploy we're going to deploy
this very simple pug for our smart
contract so we're going to be deploying
this pug this is the image that we're
going to use for our nft it's going to
be this adorable pug so let's go ahead
and create the rest of the contract for
this pug so the first thing we're going
to make is our constructor
it's going to take no input parameters
it's going to be a public constructor
and then we're going to go ahead and use
the erc721 constructor
which if we look at the documentation
we give it a name
and then a symbol
we're going to use the erc721
their parameters
which is going to be a name which we're
going to say is doggy and a symbol
which we're going to say is dog and
perfect
that's all i really need to do for the
first part this nft contract is actually
what's known as a factory contract
there's a main contract and in it it has
a list of all the nfts and the owners
that are of this type of nft so in this
example all the type of nft is just
going to be this pug and it's just going
to be this dog and we actually need a
function to mint new nfts based off of
this pug now we can absolutely have an
nft factory contract that only creates
one single nft but we're going to use
this factory implementation to create
multiple nfts we're going to do it with
a function called create collectable
this will create a new nft and assign it
to whoever called this function so
anybody can come here and create a new
puppy for themselves or in other words
adopt a puppy so we're going to say
function
crate collectible
public
and we're going to say returns
you went 256.
you'll see why we need to do this in a
minute now when we create this
collectible all we're doing is we're
assigning a new token id to a new owner
and if we look at the open zeppelin
erc721
github
we can see they have this safe mint
function this is the function that they
use to
mint or create a new nft
this function it's it takes a new
address 2 which is going to be the new
owner of the nft and a token id every
nft in this factory contract has a
unique token id we're going to have our
token ids start from 0 and and just
increment every time we have a new token
minted this safe mint function calls
this safement function which calls this
minting function so
if you're looking at the code here
this mint function is really the the
function that calls and creates this nft
you'll see actually that they just have
two mappings that they update
they update this owner's mapping
which is just a mapping of token ids to
the owners of the token ids
and then they update this balances
mapping
which is a mapping of owner address to
the token count so the number of tokens
that an owner actually has and that's
all that's happening when we call this
mint or in our case safement function
the difference between safe mint and
mint
is safement checks to see if a token id
has already been used or not and this
way we don't actually override who owns
tokens and who owns tokenids so we're
going to use the safement function so
first we need to think okay well we're
going to need to a way to count these
token ids so that every single person
has a unique token id
so let's create a global variable un256
public
token counter
and we'll initialize it tokencounter to
zero of course
this is the same as initializing token
counter to zero
but let's just make it very explicit so
when we create a new collectible
we're going to say uwen256
new token id is going to be equal to
this
token counter and we're going to iterate
this every time we mint a new token so
for example we're going to iterate that
in this create collectable here so new
token id equals token counter we're
going to call
this safement function since we're
inheriting it from open zeppelin's
erc721 we need to give it this new nft
and owner which is going to be
message.sender so whoever calls this
function
and then we need to give it
a unique token id which is going to be
this new token id now whenever we mint
one we're going to want to
increment this token counter so then we
can say token counter
equals token counter plus one
and we can then return
this new token id so we'll return the
token id of the token that we just
created and boom if you're looking for
an incredibly minimalistic contract to
deploy nfts this is all that you need so
we can run brownie compile
to make sure we did everything right
and project has been compiled we can see
it in the build so great job obviously
this might be a little dissatisfying to
you after the breakdown that we just
gave how do we view this token what does
this token look like i thought we wanted
this to be a doggy how do we know that
this looks like a dog how do we get this
image on the blockchain this is where
metadata is going to come into play now
if we look at the original erc 721 there
is this part called the metadata
extension is optional for erc 721 smart
contracts as we've talked about anytime
you make a transaction on chain it costs
some gas even very tiny amounts of data
can cost more and more gas images are
much bigger than these little bits of
data here and they can cost a lot more
gas
so when this standard was being created
the developers kept this in mind and
knew that storing entire images and
entire gifs and entire videos on chain
was going to be incredibly costly so
they added this piece about metadatas
and token uris the token uri is a
distinct uniform resource identifier for
a given asset this is an example of a
uri and the metadata that we're going to
be demoing today a uri is just a unique
resource identifier so this can be
something like https or ipfs or any url
string that uniquely points to some
metadata your metadata file is going to
look like this
it's going to have a title
for the title of the nft
can have a type
and it can have all these different
properties or stats or attributes for
example we're going to have our pug nft
which is going to be defined like this
it's going to have a name as pug
description is going to be an adorable
pug pup and it's going to have what's
called the image uri which defines what
the token actually looks like and if we
copy paste this into another browser
we get returned this it's this token uri
with this metadata json object that's
going to enable different nft platforms
to actually render our nft so this is an
example of what this pug is going to
look like on different nft
marketplaces like openc
platforms like openc understand that
they need to show this image they need
to use this name they need to use this
description and have these traits so if
we look back at this
nft on openc we can see the name is pug
we can see the description here if we go
to levels we see its cuteness as 100 out
of 100 now this of course leads us to a
really interesting point if we're
storing the image off chain then how is
this image decentralized if we're
storing this image off chain how can we
guarantee this nft is going to stay
forever now this leads us into a little
tidbit about storing data on blockchain
as of current recording storing a lot of
data on chain can get incredibly
expensive the more data that you store
the more transactions that you have to
make to store that data on chain and the
more gas that you're going to have to
spend at the time of recording ethereum
is about little less than 900 gigabytes
in size if a ton of people were to put
full videos or movies or
massive images ethereum would grow
exponentially out of proportion and this
would become unsustainable for the
blockchain network as a whole so
ethereum isn't great for actually
storing a ton of data it can store a lot
of data but it's a lot better for doing
the logic and the smart contracts so
there are a lot of different platforms
that are actually working on this
problem of storage these platforms allow
people to store data in a decentralized
way that isn't going to exponentially
explode the size of ethereum or
different smart contract platforms the
decentralized storage methodology we're
going to work with is going to be ipfs
or interplanetary file system and this
is where we're actually going to store
our image and this is actually where
we're going to store our image so that
nft marketplaces know what our nft looks
like now here's what some protocols do
some protocols just set up a server and
set this token uri to instead be from a
decentralized service like ipfs and use
just maybe their own centralized server
this is obviously a massive issue
because if their server goes down or if
they want to change the
image or they want to change the stats
all they have to do is change it in
their server and this is why a protocol
like ipfs is going to be a lot easier
quicker and more decentralized version
of doing this the full solution is going
to be using something with ipfs and
filecoin but easy solutions to do that
are still being built out so for now
we're just going to use ipfs because
it's free it's quick and it's easy and
it can be expanded to combine with file
coin to be even easier to work with now
something else that i want to touch on
too when it comes to this metadata right
now all these nft marketplaces only know
how to pull attributes
from this token uri now if we want to
build really cool nfts that can interact
with each other having some attributes
or maybe some like like attack stats or
attack moves like in pokemon for example
or trading cards we can't just store
these in this token uri
because the blockchain doesn't know
anything about this token uri so we
actually need to store these attributes
on chain i'm really hoping in the future
a lot of these nft marketplaces are
going to get better at
and pulling metadata from on chain but
now right now any attribute that we give
our nfts we actually have to reproduce
in the token metadata and the token uri
as well so we've just learned a lot
about metadata ipfs token uris and
everything like that let's update this
simple nft to be able to render on openc
and render on these nft platforms
because right now if we were to deploy
this nobody would know what this doggie
looks like so let's give it a token uri
so in this crate collectible let's do
string
memory
token uri
and after we call this safemint function
there's another function that we're
importing
called set
token uri
and we're going to set the token uri
for the token id
and we're going to give it this token
uri
this will allow our nft to actually have
an image associated with it that we can
actually see
so let's go ahead and so let's go ahead
and create a script that's going to
deploy this nft factory contract and
then create us a collectible
so we're going to do new file we'll call
it deploy
and create
dot pi and let's jump into our script
so we'll do def main
first we need to start with an account
and
once again we can go ahead and create
helpful scripts
dot pi
we can go ahead and copy paste this get
account function in here if you want
but of course since we added this config
wallet from key we're going to go to our
browning config we'll add wallets
from key
and we're going to grab our private key
environment variable
since we're using a private key
again
we're going to create a dot env
and we need our to export private key
and we're also going to need to export
our web3
infuro
project id
so we can just copy paste for my last
project the private key web3 inferior
project id and our etherscan token so
that we can actually verify this on
chain and we'll add a new file
init
dot pi
so that older versions of python know
that this is indeed a package
so we'll go ahead and do from
scripts
dot helpful scripts
import
get account now all we have to do
is import our simple
collectible
and run
simple
collectible
equals
simple collectible
dot deploy and if we look ours and if we
look at our simple collectible we have
no constructor parameters here so we can
just do from
account
and now this will have our simple
collectable deployed now we need to
actually call this now we actually need
to call this create collectable function
and we're going to pass it a string
which is going to be this token uri
i'm going to go ahead and use this
sample token uri that is included in our
nft mix so if you're looking to get this
token uri
look up nft mix patrick collins
hopefully the github will show right up
and we can just go right to the scripts
in here
it's in the simple collectible folder
create collectable
that's the bigfoot we're going to grab
this and in our script we're going to do
sample
token uri
equals
this
now when you paste this token uri in
your browser if you can't see it you
might have to add something like ipfs
companion to your browser like this
some browsers don't natively have it so
so there is a link to ipfs companion for
this project in the github repo but now
that we have a token uri we can call
this create collectable function so
we'll do
transaction
equals
simple collectable
dot create
collectible
and we'll pass in this sample token uri
and then of course we'll do from
account
we'll do tx.weight we'll wait for one
block and then if we've done this
correctly we'll actually be able to see
this nft
on an nft marketplace like open c
so let's do a quick print line here
we'll do print
awesome
you can now
you can view your nft
at
and we'll do this in fstring
and this is where we're going to put the
openc url for this ring b
so we're going to say open c url
which is going to be equal to if we pop
over to open c if we pop over to this
open c pug here on the ring p test net
we can go ahead and grab
this first start of the string so it's
going to be https testnets.openc.io
assets and then this is the address of
the contract
so we can say openc url is going to be
this slash
and we'll put this little brackets here
slash and then another one of these and
this is because the url for here
testness.openc.io assets
it's the contract address and then the
token id on the end here so this is what
it's going to look like
so in our print line awesome you can
view your nft openc.format
simplecollectable.address
comma
and we do simplecollectable dot
token counter
minus one
for the most recently deployed one and
then we'll run this now
brownie run scripts
deploy and create
network
rink b
and awesome we get this print line here
saying
awesome you can view your nft at https
testness.openc.io just keep in mind
obviously for mainnet we can't use this
testnet.openc.io
but
assets the address of the nft contract
and then the token id as well
so if we go ahead
and click this and it looks like it's
already actually been rendered here in
openc we could even go ahead and hit
refresh metadata just in case it doesn't
show up right away but it looks like for
us it did show up right away which is
awesome some other kind of fun parts
about openc is if we go to our profile
here
we'll actually be able to see all the
nfts that we own on this testnet i've
actually deployed this this doggie twice
here once to test and then once i
actually do it great we've created our
simple collectable of course no project
is complete without some tests so let's
create some tests since we're also going
to be doing an advanced collectible i'm
going to skip the integration test and
i'm just going to write a really simple
unit test so we'll create a new folder
we'll call it unit
and in here we'll do a new file
test
simple collec
so let's create our first test we'll do
def test can
create
simple collectible
we'll just make sure that we can
actually create a simple collectible now
we'll make sure that this is our unit
tests so we'll do from scripts dot
helpful scripts
import local blockchain environments
and then we'll do if
network.showactive
not in
local blockchain environments
pi test.skip
so of course we need to do from
brownie
import
network
and then also import pi test
now something that we could do here is
actually in our test we could go ahead
and even test our scripts by importing
uh deploy and create here and testing
this we do something like return
simple collectible
and in our test then we could do
from scripts
dot deploy and create import deploy and
create
and then back in our deploy and create
script we can modify this a little bit
instead of main here we'll call this
deploy and create and then we'll have
our main function
just call
deploy and create
and you'll see ronnie runs scripts
deploying create to pi if we go ahead
and run this again we can just run this
on the development network real quick
instead of on ring p you'll see that
this does also work obviously we won't
actually be able to see our nft on openc
because this is deployed to the brownie
temporary ganache chain as opposed to a
persistent wrinkly chain in our test
here
we could then just do we just run
simple
collectible
equals deploy and create
and then we'll do an assert here we'll
assert
simple collectible
that owner of zero
is going to be equal to get account
and then we'll also import
get account
so we can run brownie test
make sure this works and perfect now
this was all fun and dandy but there's a
couple of things that we didn't go over
and that we didn't do so let's create a
quick readme.md for a couple of notes
so number one
we didn't upload an image
to ipfs ourselves so we just used a
token uri that was already existing
right we didn't actually upload
something to ipfs we didn't go over why
is ipfs
decentralized we didn't really talk too
much about what ipfs is number three
anyone can mint an
nft here
with any type of stats right it's not
going to be it's not verifiably scarce
or random right this isn't that cool so
we want to actually build an nft project
that has all these pieces where we
upload the image to ipfs ourselves we're
going to talk a little bit more about
why ipfs is decentralized and it's the
preferred solution for storing nft
metadata and we're going to make our nft
more verifiably random and verifiably
scarce like for things like ethercards
and avagoji let's go ahead and do this
project again but we'll integrate the
chain link vrf
to make this nft verifiably scarce and
verifiably random and then we'll also
teach you guys how to upload to ipfs and
work with ipfs ourselves so let's go
ahead and do this so let's create a new
file in our contracts and we'll call it
advanced
collectible dot sol and what we're going
to do here is we're going to make again
an nfc contract
where the token uri
can be one of three different dogs so if
we look at this nft mix in the images
section there's a pug a shibba in you
and a saint bernard or one of these
three dogs
we're gonna make it so that when you
mint one of these nfts you're gonna get
you're gonna get a random one of these
three dogs now i'm not gonna go over
stat generation
and like creating battle battling nfts
or really games out of these nfts if you
guys wanna see a version of those
contracts check out this dungeons and
dragons nft there's a link in the github
to see this and it actually creates
characters that can do battle and have
like stats and attributes like
um like attack
and different things you'd find in
dungeons and dragons this one's done
actually with truffle as opposed to
being done with brownie but all the
contracts are going to be the same other
than this migrations.soul so if you're
looking to check this out you absolutely
can it is a ton of fun and they have
some really cool images as well so be
sure to check that out if you're looking
for more anyways here's what we're going
to be looking to do we're going to make
an nft contract where the token uri can
be one of three different types of dogs
and it's going to be randomly selected
so let's go ahead and do it so first
again we're going to do this spx license
identifier right at the top so we can go
ahead and put that there
and we're going to even use
same solidity version and we're going to
use open zipline again so
we can literally just copy and paste
that from our last project now we're
going to create our contract
advanced
collectible
we're going to say is erc
721
great
and then since we're going to want to
work with chain link vrf to get a
provably random nft we're also going to
want to import
at chain link
contracts
slash src
v0.6 vrf con
consumer
base dot sol
and of course that means we're going to
go back to here and we're going to add
smart contract kit
slash chain link
brownie
contracts
at 1.1.1 and then we're going to go
ahead
and add the remapping in
we'll say
at chain link equals
boom
awesome so we've imported the chain link
bit
our advanced collectible is erc 721 and
it's going to be vrf
consumer base so same as always let's go
ahead and start with the constructor we
know from our lottery smart contract
that we're actually going to want to
parameterize a lot of these pieces for
working with the vrf coordinator for
working on different chains and
different test nets
so we're going to do address
vrf
coordinator we're going to do address
link token
bytes32
keyhash
and we can always head back over to
docs.chain.link go to get a random
number just in case we forget what some
of the parameters are vrf coordinator
link token keyhash and fee
great you went 256 feet
i will make this
public as well
add a little curly bracket there
and we can go ahead and start doing the
rest of this of course we need to do the
vrf consumer based constructor and the
erc721 constructor
so
vrf consumer base
is going to be this vrf coordinator
and this link token
and the erc 721
we could paramore ties these as well but
we know it's going to be a dog so we'll
do doggy and the symbol of dog
which is the same
as our simple collectible here we know
we're also going to need to do this
token counter bit
so we'll do
you want 256
token counter
and right in here
we're going to do
token counter
equals zero of course we're going to
need a key hash
so let's make this unit 56 public token
counter
excuse me
we're going to do a bytes32
public key hash
and we're going to do
a uint256
public fee
and we'll set
key hash
equals
key hash
and fee equals
fee
great so this is a combination of a lot
of the stuff we did in our lottery smart
contract and some of the pieces that
from our erc 721 we need the key hash
the fee vrf coordinator link token all
for the vrf consumer base
oops i should put a extra quote here and
then we need dog doggy and a token
counter for erc 721 so now
we're going to create
our function create collectable
so we're going to do function
create collectible
and again we're going to do a string
memory token uri
but this time in our python scripts
we're actually going to define where
we're getting this token uri from and
we're going to create it ourselves but
we're going to make this public
and it's going to return
a bytes32 remember way back in our
lottery when we did this event requested
lottery winner when we called the
chainlink vrf we're going to do a
similar thing here where we're going to
make an event for whenever we request
one of these new dogs and that is also
what we're going to return we're going
to return that request id here so since
we're using the chainlink vrf here we
can go ahead and call that request
randomness function which again
over the docs.chain.link this is
imported from the erc721
and then in that request and receive
model it's going to call back with our
fulfill randomness function we're going
to need to do a couple of different
things here because we want the user who
called create collectable to be the same
user who gets assigned the token id
so first we'll do bytes 32
request id equals request
randomness
and we're going to pass obviously the
key hash
and the fee
this is going to create our randomness
request to get a random breed for our
dogs so let's go ahead and just define a
little bit of the fulfill randomness
function so we can figure out how we're
actually going to pick a random dog well
the first thing that we're going to need
is we're going to need some definition
of what the different breeds that the
dog can actually be and again similar to
the lottery we're going to create a new
type called breed using the enum
so we're going to do enum breed
and then we're going to give it three
types
pug which is going to be state 0
shiba inu which is going to be state 1
and say bernard which is going to be
state 3. so our breed is going to be one
of these three breeds here so then in
our function
[Music]
fulfill randomness
when we get that random number back we
can use that random number to pick one
of these three breeds
so of course we need to have a byte32
request id and uint256
random number
and we're going to make this internal
override so that only the vrf
coordinator can call this and what we're
going to do now is we're going to select
a breed based off of this random number
so we're going to say breed
breed which we're saying
this breed variable is of type breed
it's going to be equal to
breed generated from that random number
mod 3.
since we have one two
three different breeds awesome so this
is how we're going to get our random
breed however we do need to assign this
breed to its token id so now that we
have a random breedback how do we
actually go ahead and assign this well
we're going to have to create a mapping
to do this it'll look something like
token id
2
breed we're going to have to get our
token id somehow
and we're going to have to equal it to
the breed
so then our first question is okay well
in order for us to assign this breed to
the token id
how do we actually get the token id well
we're going to grab the token id by
doing
uin256
new token id
equals
token counter
and then
we'll just set the token id to breed
using this new token id equal to the
breed so we're going to want to make
this token id to breed
mapping up here
so which we can do
mapping
uint256
map2
breed
and we'll call it
tokenid to breed this way each token id
is going to have
a very specific breed based off of this
mapping's results perfect okay what else
do we need in this fulfillment we need
to mint the nft and we need to set a
token uri well when we minted it before
we call this safement function however
message.sender here is always going to
be the vrf coordinator since the vrf
coordinator is actually the one calling
this fulfill randomness so we can't
actually have this just be
message.sender we need to figure out how
we can get the original caller of create
collectable here how do we get
the original message.sender of create
collectable
well the answer there is actually going
to be in another mapping when we call
create collectable we can create a
mapping of request
id
to
[Music]
sender and this is going to take the
request id as a key
and then whoever sent it as the value
so we're going to create this new
mapping at the top
and then actually let's make this other
mapping public as well
we'll do
mapping bytes32
to
address
we'll call this public
request id
to
sender now in our fulfill function the
same request id that requested the
random breed is returned so what we can
do is we can say address
owner
or sender
is going to equal
request id to sender
of request id
and then this address owner is who we're
going to safemint the nft to and of
course while we're matching up the
functions we don't want to forget to
always do token counter equals token
counter plus one at the end
awesome now we still need to set the
token uri here
so back in our advanced collectable
we're gonna have to do this set token
uri at some point so let's actually
think about this for a second
we're only going to know breed of our
dog once this random number is returned
and we know the breed of the dog is
going to be one of these three breeds
it's going to be a bug a shiba inu or a
saint bernard and let's actually for now
let's even just go ahead and add those
three images to our project here create
a new folder
we'll call it image
and you can put whatever images you want
here i'm actually just going to download
i'm actually just going to download the
three images right from
the nft mix boom and now i have my pug
my shiba inu and my saint bernard in
here so anyways it's going to be a pug
shipping in you or a saint bernard here
we're only going to know what the breed
is once the random number is returned
and the breed is actually going to
govern if it's a pug ship in you or a
saint bernard so we technically could
actually just get rid
of the input parameters for crate
collectible since there's going to be no
token uri initially created what we
could do is we could create a new set
token uri function that sets the token
uri based on
the breed of the dog for the simplicity
of this project we're actually just
going to create our own set token uri
function that we're going to update
based off the breed of the dog a
challenge for you after we finish this
project is to make this even more
decentralized and have the fulfill
randomness function actually
be the one to decide what the token uri
is but for now in our fulfill randomness
function we're going to skip setting the
token uri and we're actually going to
call it in a separate function we're
going to create our own
function called set
token uri
and we're going to pass it a uin256
token id
a string
memory
token uri
and we're going to make this a public
function once this fulfill randomness
function is responded the breed of the
dog is going to be set right this token
id to breed is going to say hey this
token id
now is associated with this breed which
is going to be pug shiba inu or saint
bernard all we want to do then is now
that we have the on chain metadata we're
just going to reciprocate that with the
off chain metadata so we're going to
need three token uris for those three
dogs we're going to need one for pug
ship inu and then obviously saint
bernard however we want to make it so
that only the owner of the token id can
actually be the one to update the token
uri
so we can use a require function for
this we can say require and we're going
to use an imported open zeppelin
function called is approved or owner
message sender
token id
and we're gonna do comma here
erc 721
caller
is not owner nor approved
this is approved or own a function if we
go into the erc 721 github for open
zeppelin
we can find this this function is
approved or owner which checks the owner
of the erc721 of that token id and it
makes it so that only the owner or
somebody approved to work with this
token id can actually change the token
uri so then we're just going to call
that function called set token uri of
the
token id
and the token uri now we're actually
manually going to be the ones to call
this set token uri once the breed has
been decided we could of course like i
said use a mapping at the top that
automatically routes it there but so
that we can experiment a little bit more
and learn a little bit more about ipfs
we're gonna leave it a little bit more
general like this and perfect this is
pretty much the majority of what we're
going to need for our erc 721 contract
obviously we still need to work with
ipfs and getting our token uri but for
the most part this is everything that we
need now i do i am going to introduce a
new best practice here whenever we
update a mapping typically a good best
practice is going to actually be to omit
an event so let's create an event for
each one of these mapping updates we'll
call it event
requested collectible
and we'll do a bytes32
indexed
request id
and we'll also do a
address
requester this requested collectible
event is going to be omitted when we
request id to sender because we're
updating the mapping here this is also
going to be really helpful when we run
our tests so we can get this request id
similar to what we did with the lottery
so down here we're going to do omit
requested collectible let's collect
dibble here
let's use an i instead of an a here
collectible
and we'll pass it
this request id
and then message.sender
we also update a mapping down here with
tokenid to breed
so we're going to do a new event
we're going to call event
breed assigned
and we'll do uint256
indexed
token id
and then we'll do a breed
breed
and then when we assign the breed here
we're going to omit
breed assigned
with
new token id
and breed
so let's see if we did everything right
let's do brownie compile
looks like we have a quick error here
did you mean fee or fee
let's
do a quick underscore there
now let's try to compile
much nicer all right great let's move on
all right so now let's take a little
look-see at our scripts here so we have
this deploy and create script which is
going to work for our simple collectable
so let's go ahead and actually give them
both their own folder so we're going to
do a new folder
we'll call one simple
collectible
and we'll do another new folder
called advanced
collectible and we'll grab this original
deploy and crate and we'll place it into
this simple collectable folder here
awesome
now if we wanted to run this we would do
brownie
run scripts
simple collectible deploy and create and
we can go ahead and test this out on our
local ganache here
and cool looks like it's working
correctly great so now let's create our
advanced collectable script and a lot of
what we're going to do is going to be
the same as this simple one deploy and
create so i'm actually going to copy
this
we're going to create a new file called
deploy and create
dot pi we're going to paste everything
in here but we are going to change a
couple things up so let's do a little
bit of refactoring first so this opencrl
we're going to be accessing in a couple
different scripts so we're actually
going to take this
copy it
get rid of it in our deploy and create
here
and we're going to move it to our
helpful scripts
and place it under here openc url equals
this script right here
and now what we do in our simple
deploy and create
is we're going to do from
scripts.helpfulscript
import
openc url
we're going to delete that here
so now in this script
this openc url is going to come from our
helpful scripts which is what we want
and we're going to do the same thing for
our deploying create for advanced
okay great so i've now copied and pasted
all the code from deploying create into
this deploy and create for our advanced
collectable so let's go ahead and modify
this now
so instead of from brownie import simple
collectible we're going to import
advanced
collectible
and we're going to do the same thing
down here
and i'm just going to go ahead and
delete everything
before this we're going to change this
to advanced
collectible
and awesome okay this is going to be our
starting point and we actually we can
even get rid of this sample token uri
great so this is going to be our new
starting point we've done a little bit
of refactoring now openc url is going to
be in the helpful scripts we're pulling
in advanced collectible instead of
simple collectable and the rest applies
we're still using our get account to get
the account and now we have this
advanced collectible equals
advancedcollectable.deploy
of course
our advanced collectable has a different
constructor
it's got a vrf coordinator a link token
a key hash and a fee so we're going to
have to add those
as the parameters in here we want to
work with ringpi for this because the
openc marketplace right now for test
nets only works with rinkby so that's
why we're going to work with ringby here
so let's get started and just grab those
ringpie addresses first
so our advanced collectable needs a vrf
coordinator and a link token so if we
head over to the chainlink documentation
we go to contract addresses for the vrf
we can scroll down to
rank b
we'll grab the vrf coordinator here and
same as before
we'll jump into our browning config
we'll do
networks
rinkaby
and we'll do vrf
core did nator
we're also going to need the
link token here
so we'll do link token
we need the key hash
key hash
and we need the fee which is going to be
0.1 link which we can do fee as one one
two three four five six seven eight nine
ten one two three four five six seven
which can be 0.1 you can of course just
copy and paste brownie configs over to
different projects because
because these values are always going to
be the same now on our advanced
collectable deploy and create we can go
ahead and add those variables in here
since we're going to be interacting with
actual contracts that are on chain and
we're going to want to be able to flip
back and forth between the mock versions
of them we're going to bring back that
get contract function that we used
before this is the function that's going
to be smart enough to know if we need to
deploy a mock or just grab from an
actual contract i'm going to show a
little fast forward of me rebuilding
this function but feel free to copy and
paste it from our last project now
something that we do need to talk about
though is our deploy mocks function the
syntax here is going to be basically
exactly the same however we do need to
deploy a couple of mocks so make sure
you have these in your deploy marks
function
specifically we're going to need a mock
link token and a mock vrf coordinator
and again feel free to just grab these
from our last projects
and then of course be sure to add your
contract to mock dictionary where the
link token is mapped to the link token
and the vrf coordinator is mapped to the
vrf coordinator if you guys look in the
github repo there's a couple try catches
there that just make it a little bit
nicer for error handling
but this is basically the entire script
so now what we can do we can go back to
our advanced collectable deploy and
create
import this get contract from our
helpful scripts
and we'll just replace this with get
contract
vrf coordinator
get contract
link
token and then for key hash and fee
since these don't really matter these
can be whatever we want and these aren't
really contracts
we can go back to our config
we'll add
the development network and we'll just
add key hash
and fee
and again since it's just testing we can
just go ahead and make them exactly the
same as ring b
done a lot of work now let's go ahead
and run this on the development network
again so we'll do brownie
run scripts
advanced
deploy and create
no network so it's going to default to
development let's see what happens here
and awesome so we can see we actually
did a couple of things here
so first we deployed this mock link
token
then we deployed our mock vrf
coordinator
we finished that and then we deployed
our advanced collectible all on a local
network so let's go ahead and continue
here once we deploy this code we're
going to want to fund this contract with
some link the reason we're going to want
to fund it with some link of course
is that we can call the random number i
like to have my funding with link also
in a function so we'll do fund with link
and we'll give an address
advancedcollectable.address
and let's go ahead and create this
function in fastforward we're going to
fast forward this as well but feel free
to copy and paste your fund with link
functions from past projects or if you
want to slow this down and follow along
feel free to do that too
let's go back to our deploy and create
we now have this fund with link that
we're going to do right here and then
all we have to do now
is call our create collectable function
here so we'll just do advanced
collectible
dot
create collectible
of course
from
account
and we'll do
creating tx
we'll wait one block confirmation
and then we'll print
your token has been created
so we are definitely going to want to
test this because we have a number of
custom scripts here right
so let's go ahead and just do a manual
test
so we'll do brownie
run scripts
advanced collectible
deploy and create and we'll do it on a
development network
whoops we got to add ether here sorry
about that in the web 3.2 way one ether
so let's go ahead and run this script
again
and all right it looks like everything
worked everything was deployed new token
has been created
great this is fantastic now ideally
before we do an integration test we
would of course write some tests but i
want to teach some things that are
easier to demonstrate on an actual test
net so we're going to go ahead and
deploy this to an actual test dent
before we write our tests so we're just
going to run the script again
and do dash dash network
rank b
and awesome a new token has been created
so what we can do
is we can grab the contract address once
again
we'll paste it into the rank b ether
scan
and we can see everything in here we can
see we've given it a little bit of link
we can see our two function calls one is
going to be the contract creation one is
going to be create collectable
our contract has already been auto
verified actually because i verified
this contract on rank b already and
etherscan says ah this bytecode is the
exact same of another contract that
we've already verified and if we go to
read contract and we go to token counter
we'll see
one token has been created
we've actually created our first token
now what we can do in our advanced
collectable scripts we can create a new
script and just call it create
collectable
dot pi
and in here we'll just create a
collectable
so well all we have to do is we'll do
def main per usual
we'll have to do from
brownie
import advanced
collectible
we'll import accounts from our helpful
scripts
we'll import
fund with link
in our main function we'll do account
equals get account
of course we need to import this as well
for my helpful scripts
then we'll do
advanced
collectible
equals
advanced collectible minus one because
we just want to get the most recently
deployed we'll fund this contract with
link so we'll do advanced
collectible.address
and we'll also choose an amount here
we'll just do web3.2
way
of 0.1
with ether
that means we also have to do from web3
import
web3
then
we'll do transaction
then we'll do
creation transaction
equals
advanced collectible
dot create
collectible
from
account
we'll do creation transaction dot wait
we'll wait one block confirmation
and then we'll print
collectible
created
oops sorry i actually don't have to
import account here or accounts excuse
me
and sorry this actually needs to be
amount equals excuse me
now let's go ahead and run this and what
we're going to do
is we're going to fund our advanced
collectible with link which is 0.1 link
and then we're going to create a new nft
awesome collectible created so if once
again
we take this address
go back over to etherscan
do a quick refresh here
we go to our contract read contract
we'll look at the token counter it may
still be one so you might have to give
it a second for the chain link vrf to
respond
once the chain vrf responds we'll see 2
in here we can also check the token id
to breed
if we look at 0 with 1 we'll see the
breed
is 2.
and if we look back at our contract
the advanced collectible without soul we
know that if the breed is two that means
it's a saint bernard
see the token id of one
it has a breed of one so it got randomly
assigned a shiva inu
awesome so we have tokens and they're
get randomly assigned breeds fantastic
as you can see we're doing kind of a lot
of manual testing work here right so
what we're probably going to want to do
instead is you guessed it automate these
tests
now go ahead and want to deploy dance
import that deploy script that we just
wrote
so we would do
from scripts
dot advanced collectible
dot deploy and create
import deploy and create
and then all we have to do is call
deploy and create
in this function we'd probably want to
then return the advanced collectible
contract so we can make sure that we
actually get what we want here
so we'll say advanced collectible
equals deploy and create
and that'll be our acting
step
beginning we'll do arrange
then we'll do an assert
of
we'll just check to see
that the token counter has been
increased we'll do assert
advanced collectible
the token counter
is equal to one all right great so this
will return our advanced collectable
however we know that since we're
actually going to be working with a mock
vref coordinator if we look at our
advanced collectible
we know that the bulk of the work
actually comes in this fulfill
randomness function and we're going to
have to tell our mock to actually return
and call this function so in order to do
that we should probably also return this
creating transaction here so that we can
get the request id remember how in our
lottery we actually just directly called
everything
and we needed this request id to call
this callback with randomness function
in our test here we're actually using
our scripts a little bit so we could
either just go ahead and write out all
the steps similar to what we did in the
lottery or we could adjust our scripts a
little bit for simplicity here we're
just going to go ahead and have this
deploy and create function also return
the creating transaction this way we can
go ahead and get the request id so back
in our test here that means we have to
do deploy and create
equals advanced collectible and
creation
transaction now that we have this
creation transaction we can use it to
get our events
and again if we look back in our
advanced collectible we can see here
that we're omitting this requested
collectible with request id so we can go
and do request id
equals creation transaction dot events
we'll add the name
of our event here which is requested
collectible and then we'll get
that request id once we have this
request id we can then go ahead and grab
the vrf coordinator so from our scripts
we'll grab this get contract
and we've coded our get contract in a
way that if the mock has already been
deployed again if we go back to our
helpful scripts if the contract has
already been deployed then we're just
going to go ahead and grab it so since
here our mock will have already been
deployed so we don't have to redeploy it
so we can just do get contract
vrf
core did nator
dot call back
with
randomness
and we'll use the request id
we'll pick some number like 777 we'll
give it to
the address of our advanced collectible
and remember we're going to be calling
the callback with randomness this is
what a real chain link node is actually
going to call back and it just needs a
request id a randomness number and a
consumer contract
so request id random number and then the
consumer contract
and then of course we have to do a from
account
from get account
and we'll import get account as well
now we can move into our cert phase
so first if this is correct then our
token counter
should be at least one so we can assert
advanced collectible
dot token counter
is greater than zero
or we could be a little bit more
specific here
equals equals
one we also should technically be able
to get the breed and figure out the
breed of this first token of this first
collectible let's go ahead and
parameterize the 777 we'll call it
random number
equals 777.
we'll place that here
and then what we can do is we can say
certain
collectible
dot token id
to breed
of zero
right in our fulfill randomness we're
going to assign the token id
to being the breed and the breed is
going to be this random number mod 3.
so on our test we can say
the token id to breed of dog 0 is going
to be equal to
random number
mod
3 and this is pretty much our full test
so let's go ahead and run this
we can do that test with dash k
whoops it looks like our simple test has
actually got an error now we're getting
this module not found no module named
scripts.deploy.create
this now since we actually changed it
it's going to be
scripts.simplecollectable.deploy and
create
so now if we rerun our test
we'll see brownie isn't going to err out
anymore
so even though we skipped this test
brownie still compiles it to make sure
that everything makes sense but what we
see here is fantastic our advanced
collectible unit test has worked
perfectly let's go ahead and make an
integration test for our advanced
collectible here so now we'll have our
test folder here and we'll have unit and
we'll have integration
our integration test is actually going
to look really similar to our advanced
collectable here so i'm just going to go
ahead and copy everything new file
test
advanced
collectible
integration
pi
and we'll just paste everything in here
now the only thing that we're going to
have to change is that we're not going
to be the ones to call back with
randomness here
so we can remove this part
we also don't need the request id
anymore since the chain link node is
going to be responding this means that
the breed that we're going to get is
actually going to be random so we can
get rid of that assert as well all we
need to do is wait for the transaction
to get called back
so we're going to import time
and instead of us calling back with
randomness
we're just going to do
time dot sleep
then we'll wait 60 seconds
test can create collectible we should
also give this a different name
integration
now we should be able to test this on a
ring b chain and our token counter
should indeed increase with the chain
link node actually responding so now we
can run brownie test dash k
just that test dash dash network
rink b
oh whoops right now we're skipping this
because we're saying only for local
testing now since this is going to be
our integration test we're going to do
the opposite
if network.showactive is in these local
blockchain environments then we're going
to skip it and say only for
integration testing
all right great so now we have a quick
and dirty integration test that we can
run we're not going to run it for now
because we're going to be working a lot
with this rigby chain and we're going to
be deploying a lot of different things
and we don't want to wait so long so
this is fantastic we have a way to
deploy this we have a way to get these
new collectible tokens and create them
but if we were to take this address
right now and try to view this token on
something like openc
we would get nothing back we wouldn't
get any result right now our token
doesn't have a way to be viewed or be
visible by everybody else these mt
platforms don't know what they look like
and again this is where that set token
uri is going to come into play
so we have to figure out a way to host
an image and host all the metadata for
our token uri
and the way that we're going to do this
is by using
ipfs and this is a lot better than
actually hosting this on our own server
because anybody can then go ahead and
host this image or this metadata
themselves
now there's further improvements to this
with something like filecoin
where you actually pay to have your
image hosted forever however ipfs can
hook into filecoin in the future and is
going to be a good enough solution for
what we're looking to do here
just keep in mind that what we do not
want to do is run this on a centralized
server when we spin up our ipfs node we
will be the only node that actually runs
and actually hosts our image however the
image is open for anyone to pin to their
nodes as well
so it's much easier for us to host our
images in a decentralized manner what's
bad obviously is if we just had the
image stored on our own centralized
server because if our server goes down
then that url no longer exists if at
least one node on the ipfs network is
hosting this image it will be available
for anybody to see so that's why it's
going to be a much better solution than
some centralized server as i mentioned
decentralized storage is a topic that's
getting better and better and we're
looking forward to seeing more and more
ways to interact with them in any case
we need to create an ipfs node that's
going to host some data that looks like
this or like what we saw with our simple
collectable
it needs to host metadata that will look
like this we both have to host a
metadata file and an image uri file
which will host the actual image
both of these need to be stored on ipfs
so let's go ahead and create a new
script called
create
metadata
which will read off chain and create our
metadata file so we'll start our scripts
per usual
with def main
and we'll get the most recently deployed
advanced collectible
using this -1 syntax
of course we're going to do from
browning
import
advanced
collectible once we have this advanced
collectible we can then loop through all
of the tokens and actually figure out
the metadata for each one of them so
we'll do
number
of advanced
collect
bowls
equals
advanced collectible.tokencounter
because we want this crate metadata to
create the metadata for every single
token that we've created do a quick
print line here just saying print
you
have created
number of collectibles
collectibles
we even run this really quick brownie
run scripts
advanced
create metadata
network rank b since we've already run
this on the ringpi chain
we'll see you've created one collectible
if i were to run our create collectable
script again and then our create
metadata script would of course get more
but right now we only have one
collectible
now let's loop through all these
collectables and create their metadata
so we're going to create that that file
it looks like this and it's going to
have it's going to have the name which
is going to be based off of the random
breed that i got it's going to have the
description which is based off of again
the random breed that i got it's going
to have an image which will also be
based on the random breed that it got
and i just put some attributes in here
but again these attributes so we're
going to say for each token id
in the range
of number of advanced collectibles
for each one of these advanced
collectibles
first we need to get the breed so we're
going to say the breed the breed is
going to be equal to advanced
collectible dot token id
to breed
of the token id
now advanced collectible that token id
to breed this is going to return an
integer right because again our advanced
collectible
this enum breed is going to be 0 one or
two so we actually want to create a
quick mapping that represents that zero
is pug one is shipped in u and two is
saint bernard so i actually like to
create this in a helpful script
called def get breed
and then it takes as an input it takes a
breed
number
and it uses a switch statement so up top
we'll say
breed mapping
equals
zero is going to be pug
one is going to be
shiba inu
and two
is going to be saint bernard
so in this get breed function now
we can just do return
breed mapping
of that breed number that we get
so
instead of doing advanced collectible
the token id to breed we can now just do
get breed
and this will this will return the
number and this will return the actual
string so we can just do from scripts
dot helpful scripts import get
read
now that we have the breed we can start
creating this metadata file now what
we're going to want to do is we're going
to want to have some type of format for
our contract to always pull from so what
i like to do here is i'll create a new
folder
called metadata
and in this folder
i'll have a new file
called samplemetadata.pi
and then i just have metadata
template
equals and i'll just have this this
template that we're always going to use
now in here we're going to need a name
and then
we're going to leave the name blank
because we're going to want to fix it
later
we're going to have a
description which we're also going to
leave blank for now
we're going to have that image uri which
will also leave blank
and then we're going to have some
attributes which should be blank for
this dog because we don't actually have
any on-chain attributes but i'm just
going to go ahead and add some to show
you what you could do if you wanted to
give your dog some stats you know maybe
maybe cuteness maybe
maybe raw power maybe speed agility you
know whatever you want to do so we'll do
trait
type
gonna be cuteness
and then
value is gonna be 100. this would
basically say hey there's a trait type
called cuteness and the value of that is
a hundred so the cuteness of the dog is
100. so now once we have this sample
metadata file we can import this into
our script here so we'll say from
metadata
dot sample metadata
import
metadata template
and another quick note you might have to
put a underscore underscore init
underscore underscore dot pi file in
that metadata folder
if you're working on older versions of
python and we start creating our new
metadata file for this break for this
dog we want to save each collectible
under their network and with their token
id so let's go ahead and create a new
folder
call it rink b and this is where we'll
save all of the rink b metadata for all
these collectables for all these token
ids now before we actually save it
though we should just check to make sure
that the file doesn't already exist
right because if the file already exists
that means we've already created the
metadata for that token and we don't
need to
so we can just go ahead and get the
metadata
file name
which is going to be equal to
dot slash metadata
slash network dot show active
of course this means we need to import
network from brownie
slash
the token id
token id with a hyphen
with the breed
dot json
just to make sure we're doing this right
we can even just print this out
do a quick manual test
brownie run scripts
advanced
create metadata
network rink b
so this will be the name of the file so
metadata rink b
token id and then the
breed.json okay cool now we can actually
check this to see if this already exists
and we're going to use a python library
called path so we're going to say from
pathlib
import path
and we're going to say if that path
this metadata file name
dot exists
if that path exists
we'll do a quick print saying
metadata file name
already
exists
delete it to overwrite
this way we won't accidentally overwrite
metadata that we've already created and
do extra work so if it exists we'll
print that out great otherwise
we can go ahead and print
print def
creating metadata file
metadata file name
you can even run this real quick
great you have one collectible
creating metadata file perfect
so let's go ahead and start creating
this metadata file so we're have to give
it a name description
image uri and we're not gonna give it
any attributes though so just name
description and image uri so name is
easy enough since this is a dictionary
or a mapping in python we can actually
just go ahead and start mapping so up
above before this if
we'll do
collectible
metadata it's going to be equal to
this template
so this is going to be where all we sort
all of our metadata and we'll say
collectible metadata of name
is just going to be the breed so if it's
a pug the name will be pog if it's
shipped in you name it will be shipped
in you if it's st bernard name will be
saint bernard and we'll give it
collection metadata
description
is going to be equal to
we're going to do an f string here
and adorable
breed
pop
now if we print out this collectible
metadata we should see
at least the start of the metadata which
we do great name saint bernard
description and adorable saint bernard
pup of course you'll have a different
random breed but it should look
something like this
now we're going to need
collectible metadata
image uri
this is where we're going to have to
have our image already uploaded to ipfs
so we can assign it to our metadata here
so how are we going to do this well
we're probably going to need some upload
to ipfs function it's going to return
our image uri and then we can just set
that image uri to the collectible
metadata
of image
so let's go ahead and start doing that
let's create
our upload to ipfs function now in order
to upload to ipfs we of course need to
have the images ourselves i already have
them downloaded here and again you can
download them right from the github
yourselves if you like to make this a
little bit generic we'll have this
upload to ipfs take a file path
that way we can pass
this imagery upload to ipfs we're going
to give it some type of file path here
we're going to have to grab that image
path so we'll grab that image file name
by just doing breed
dot lower
because right now our breeds are all
upper case so we're going to want to
make a lower case then we're going to
replace
the underscores with
hyphens
dot png
so we'll say plus
dot png
and then you know let's just go ahead
and add the full path here so we'll say
dot slash image
slash
plus
3. lower perfect
so and then we'll even change this
to image path and then we can pass this
to our upload to ipfs so this file path
now is going to be the location of the
object that we're going to upload to
ipfs we're going to use this path
library to actually grab that path to
upload it to ipfs so we're going to say
with path
file path
dot open
rb
as file path
now this is a little bit of
sophisticated python here what we're
doing is we're taking this path here
we're opening the file rb means we're
going to open it in binary since these
are images that's how we're going to
actually
open it and we're going to upload the
binary actually to ipfs and then as fat
fp so we're saying this opened file
is going to be named fp or file path
we're going to do image
binary
equals fp.read
and that's how we actually read the
whole binary and now this whole image is
stored as binary in this image binary
here now here's where we're going to do
the upload stuff now to get started here
we're actually going to have to download
the command line for ipfs download
command line ipfs
we'll come right to the docs here and
again there's going to be a link
in that github and in here there are
instructions to
to download it for whatever system that
you're working on right if you're
working on windows if you're on linux if
you're on mac these are the different
ways to actually download this ipfs
command line you'll know you've done it
right if you can type ipfs
version and you see something like ipfs
version 0.9.0 it's important to note
that we could also do the ipfs download
desktop
and we could download the desktop
version of this and we'd see a user
interface which looks something like
this we could upload our files manually
and then manually go ahead and
grab those files and place it into our
scripts but we're engineers we want to
do this programmatically in any case
once we have this api downloaded we can
actually follow the documentation here
the http api reference for actually
uploading our code we're going to be
mainly working with this endpoint api v0
slash add as this is the endpoint that's
actually going to add our file or
directory to ipfs now what we're going
to want to do is we're going to actually
upload our images to our own ipfs node
we can run our own ips node by doing
ipfs
daemon and we'll see an output that
looks something like this we can even
see a web ui using this web ui url here
this will look similar to what the ipfs
desktop looks like but again we're going
to work just mainly from this damien
from our own ips note congratulations
you're running your own ipf's node right
now as you can see it's currently
running on our own localhost right here
http 127 0.0.1 at port 5001. so to
actually upload this we're we first need
to get that ipfs url
which is going to be equal to
this url right here
paste
now we want to make an api call or a
post request to this
endpoint
using
this
api v0 ad and these are all the
different parameters that this ad
can actually take in
so that we can actually post it to ipfs
for those of you familiar with curl and
you want to test this out using a curl
i've added a curl into this create
metadata file as a comment so that you
can actually go ahead and test this if
you want to use this now what we're
going to want to do to keep working with
our scripts
is you should have like a little plus
button somewhere on your vs code
we're going to hit that plus button
and now we're actually going to have two
different shells one which is running
our ipfs node
and one which is running our bash or zch
or whatever other shell that your os
natively works with now that we have
this ipfs url we're going to grab the
endpoint
which is going to be
again this right here
dash api dash v0 add
and we can make a post request to it so
for us to do that we're going to say
response equals requests dot post
we're gonna do the ipfs url
plus the endpoint and we're gonna say
the files that we're gonna upload
is gonna be equal to
file
image binary
requests is a python package that we're
going to import so we're going to say
import requests
now if we go back to the ipfs
documentation we can scroll down to see
what the response looks like
it's going to return a bytes
a hash
a name
and a size
now if we look at this sample
token uri we can see the api call here
ipfs stores all its data using a hash
and if we're looking at this and if
we're looking at the simple collectible
this hash here
is the hash that represents this
pug.json file everything in ipfs gets
hashed and every single piece of data
has a unique hash which is why it's so
fantastic if we were to change anything
with this image this hash would be
drastically different all we need to do
is get the hash that ipfs gives the
image that we upload we go ahead and
plug it into a template url like this
one here so what we're going to do then
is we're going to say ipfsh
it's going to be equal to
this response.json
since
we're just going to jsonify the response
to make it look like this response here
and we're going to grab
that hash
right since it's going to return this
dictionary
we just want the hash here
then
we're going to give it a file name
by saying it's going to be that file
path
dot split we're going to do some fancy
python stuff here we're going to say -1
to 0
which basically all this line is doing
is saying you know if we have dot slash
image slash pug
dot png
we're going to remove
we're going to split it up by these
slashes
into an array and we're going to grab
the last part of the array so we're
basically just
changing this to this with this line
right here then with this we can get the
image uri which is going to be equal to
an f string again
https
ipfs.io
ipfs
slash
ipfshash
question mark file name
equals
file name
and it's this format right here which
will give us
this
so if i go ahead and even just copy
paste this under as a comment to show
you guys
we see this part's exactly the same
and then this is that hash here
represented here
and then we have question mark file name
equals
and then the file name
so excuse me this is actually gonna be
like
zero hyphen pug
zero hyphen pod and that's exactly what
we need we need this image uri so we'll
do a quick print
image
image uri
and then we'll go ahead and return
the image
uri
now since we're actually going to be
testing this with
ipfs we can add a new integration test
so we'll call this test
ipfs
upload.pi
now you might want to write a test for
this and we're not going to do one but i
challenge you to later on maybe come
back and and write your own test for
this upload to ipfs
for now we're actually just going to
manually test it
so we're going to go back up to our
script here and we're going to run image
uri equals upload to ipfs image path
and then we're going to get printed in
image url since we're working with the
saint bernard here we should get a saint
bernard image uri
so if i run brownie
run scripts
advance
create metadata
network rink b
let's see what happens i need to add
brackets here sorry about that
now let's try it again
awesome we were able to create this
metadata file
now if we go ahead and copy this
and paste it
perfect we see exactly what we're
looking for we see our saint bernard
awesome job and this has been uploaded
to our own ipfs node now i want to show
you guys actually another service and
another way we can actually upload these
to ipfs some people don't want to run
their own ipfs node because they're not
actually going to be keeping it running
the whole time anytime their node goes
down this means that nobody will be able
to see your image unless somebody else
pins your image or or uses your image so
what i also like to do is i like to
upload it to some other third-party
service as well as uploading it to my
own ipfs note so i like to create
another script actually called
deploy to pinata
so let's go to scripts new file
upload to
pinata.pi
so pinata
pinata is an ipfs file management
service and they actually will pin
whatever files that we're working with
as well so we'll have it pinned in our
node and they will have it pinned as
well so we can go ahead and register
awesome this is what pinata looks like
it's a way to upload and work with ipfs
and they'll give us some extra support
and they have a free tier which is
fantastic as well they have some
wonderful documentation as well under
this documentation section so let's go
ahead and upload this to ipfs so that
when our node goes down our images don't
go down so we'll do pinata
base
url
is going to be equal to
https dash dash api.pinata.cloud
you can find all this in the
documentation as well if we scroll down
the documentation we're going to be
using this pin file to ipfs endpoint
here and you can see that entire
endpoint right here
with the base and then the endpoint so
we're going to copy that endpoint
we're going to say endpoint
equals
pinning
pin file to ipfs we're going to choose
some file path
and for us we're just going to do dot
slash image
slash
pug.png
of course if you want to upload some
other image you can you know change this
file path or you could even do some type
of for loop to pin everything uh in the
image section here again we're going to
do file name we're going to use that
same syntax before that's
we're doing file path
dot split
slash
some fancy python stuff
just to get
this last part and we also need and we
need to use some headers in this post
request so it's a type post request we
need to use some headers here so we're
going to say headers
equals
copy this pinata api key
which is going to be some api key and
then we also have this pinata secret api
key pinata secret api key
which is going to be something else
we can find these two api keys if we
scroll all the way down we hit api keys
create a new api key
i'm going to call this you can make this
an admin key i'm just going to do limit
max users
limit max uses i'm going to set this to
200
because i'm going to make this a public
key so i don't want people using this a
million times
please make sure you select at least one
permission
pin file to ipvs for those of you guys
watching you can absolutely just grab
all these if you want you can make this
an admin you know do whatever you want
to do here since i'm only going to be
using this pin file to ipfs that's all
i'm going to do
hit create key and here are our tokens
here so our api key is going to be right
here and we're going to copy that
we're going to open back up that dot env
and add this as one of our environment
variables here so we're going to export
pinata
api key
equal to that key there
this api secret we're going to copy and
we're going to export pinata api secret
equals that key there
and we actually don't need this
jwt but if you guys wanted to you could
copy it as well
so now that we have them in our dot env
file these are now going to be
environment variables that we can use
and brownie's going to automatically put
them into our
environment
so what we can do then is we can do os
dot get env
pinata
api key
and then of course we're going to import
import os
and then
for our secret key we're going to do the
same thing os dot get env
pinata api secret
this is how we get those two headers for
uploading to pinata then we're going to
do a lot of the same code we did before
we're going to say with path
a file path dot open
rb for the binary as fp
of course since we're using path we're
going to do from path lib
import
path
we're going to do this same piece image
binary
equals fp.read
response is going to be equal to
requests which we have to import
requests
import requests
dot post
pin you have a base url
plus that endpoint that we have
and for files
oops
it's going to be equal to
file
and we're going to upload a couple of
things here though we're going to give
it a file name
we're going to do the image binary and
that is getting really annoying when it
keeps getting in the way
file name image binary
and then outside of these brackets here
we're going to do comma
headers equals
equals headers
and then we're just going to print
response.json so to have this run in
browning we're just going to do a def
main function here
a nice little trick we can do is we can
select all this text and just hit tab
and it'll move it over one
and perfect we can now run this inside
of brownie
so we can do brownie
run scripts
upload to pinata
and perfect we get a little output
that's going to look something like this
it's going to give our ipfs hash the pin
size the timestamp
so now if we go back to pinata
we go to pin manager
do a little refresh here
we now see
our pug has actually been uploaded to
pinata awesome work we're going to keep
going using the ipfs daemon to actually
upload things but if you want you could
totally swap out this upload to ipfs to
use that script that we just created to
upload it via pinata instead of our own
ipfs node anyways this upload to ipfs is
going to return this image uri so we can
go ahead then
and set the image uri it's going to be
set on this collectible metadata image
and then all we have to do is dump this
collectible metadata into its own file
and then upload that as well to ipfs
we'll dump this to its own file by doing
with
open
metadata file name
and we
open it with a w which means that we're
going to write
as file
json.dump
collectable metadata to the file
so we're going to import json to do this
and what this is going to do is just
going to dump this dictionary as json to
this collectable metadata file then we
can upload to ipfs also
this metadata file name and this upload
to ipfs should print out the image uri
or in this case the metadata uri so
let's go ahead and try this out
so remember we do need our ipfs daemon
running
let's go back to our scripts and we'll
do brownie
run scripts
advanced
create metadata
network
rank b
and boom okay so here is our image uri
which we click this will be able to see
looks just like this
and then here is our uploaded
saint bernard metadata file which is
fantastic so now we have both a metadata
file
and we have an image uri
this is fantastic we've uploaded both of
these
to our ipfs
and if we scroll over
go to our metadata file in ring b we'll
see
we have this new file in here because
we've gone ahead and saved it in here
it has everything that we need it has st
bernard
it has the description it has this image
uri that we just created and it has some
attributes that again we're basically
ignoring now to make our lives a little
bit easier and since i've already
actually uploaded these to ipfs myself a
couple times and since the hashes of
these are going to be the exact same for
all of us when we upload this we're
going to go ahead and just quickly
refactor this to make it a little bit
easier so we don't always have to have
ipfs running so in our dot env i'm going
to add a new environment variable called
upload
ipfs
and we're going to set it equal to false
so now down here i'm just going to say
if os dot get env
upload
ipfs
equals equals true
anyway since we're going to do os here
we're going to do import os
and before this i'm going to do
image uri equals none
and we're going to say
image uri
equals image uri if image uri which
again i know this could be a little
confusing but we're saying
we're setting image uri to whatever
image uri is if image uri isn't none
else we're going to create a mapping
called breed
to
image uri
of the breed so again
since i've already uploaded them i
already know what all these image uris
for these three dogs are going to be
so up at the top we're just going to
create a new mapping called breed to
image uri
equals
i'm actually just going to go ahead and
copy paste this whole thing
now you can skip this you don't have to
refactor here
and you can just always have your daemon
running and always upload to ipfs it's a
little bit quicker to not always have to
do that again this brief image uri is in
the github repo feel free to just copy
paste it to use it you can even click
the links to check it to check to see
that those image uris are really there
and this is what we'll use
so back down here reach the image uri
uri perfect and then we're also going to
add if
again os.get
env
upload ipfs
equals equals true
then we're also going to upload to ipfs
down here but this is to go and actually
just show you how exactly we could
upload all this stuff to ipfs since i've
already done it we're going to make it a
little bit easier on ourselves another
thing that you might do is you might
actually save
all these urls to their own file to
their own json object maybe inside of
the metadata folder maybe under wrinkby
or something
and then you could go ahead and just
pull directly from those files same
thing with the metadata once we upload
to ipfs we're not actually going to save
these urls anywhere you could absolutely
100 percent
after you run this upload to ipfs script
we go ahead and save it to a file and
pull directly from there moving forward
but awesome okay so
we've done a lot of work here we have
uploaded to ipfs our metadata
and our image uris so we have everything
that we need to actually just set the
token uri
finally for our advanced collectible we
finally can call this set token uri
function so let's go ahead and do this
last bit here this last set token uri
function
so let's go to scripts advanced scripts
create a new file we'll call it set
token uri
uri dot pi
and this is where we're gonna set the
token uri so we'll do def main
and in here we'll do a quick print print
f
working on
network dot show active
of course since we're using network
from browning
imports network
to close that there and let's grab the
most recent advanced
collectible
it's going to be equal to advanced
collectible
minus one
since we're using advanced collectible
contract let's import that from brownie
let's once again loop through all the
tokens that have been deployed
so we'll do number
of collectibles
equals
advanced collectible dot token counter
do a quick print
you have
print f excuse me
number of collectibles
token ids
and let's loop through this list of
collectibles again so we'll say for each
token id
in range
number of collectibles
first we'll get the breed
saying breed
equals advanced
collectible
token id to breed
of the token id
we actually have to call this
getbreed function again
which luckily we generalize so we can do
from
scripts.helpfulscripts
import
get breed
and now let's first before we actually
set the token uri let's check to see
if it already has a token uri set so
we're going to say if not advanced
collectible dot token uri
of token id
dot starts
with
https
so what this line is doing i know it's a
little bit long is we're grabbing
advanced collectible.token uri
of the token id so we're grabbing this
token ids token uri
and we're saying if it doesn't start
with https that means we know that it
hasn't been set
so we can go ahead and print
setting
token uri
let's actually make this a print f
of
token id
and then we can set the token uri so i'm
actually going to generalize this out
into its own function
so let's go ahead
and we'll do def
set
token uri
and as inputs this is going to take the
token id
the nft contract which is going to be
our advanced collectible contract
and the token uri so the first thing
that we're going to do we'll say account
equals get account
so we're going to grab this
get account of course
from our helpful scripts
because this set token uri is actually
going to call that set token uri
function we're going to say
nft contract
dot set
token uri
of the token
[Music]
and the token uri
remember this is a function that we
added to our advanced collectible right
here set token uri it takes a token id
and a token uri and this is going to be
from of course
account we just created so we're going
to say
transaction
equals that we'll do transaction.wait
wait one second for it or one block for
it and then we'll print
we'll do printf
awesome
you can view
your nft at
we use that openc url
dot format
nft contract.address comma token id
then i'm just going to add another print
here saying
please wait up to 20 minutes
and hit refresh
metadata and hit the refresh metadata
button
so now we have our set token uri
function
we can add
the token id in here
the advanced collectible contract and
then we just have to add the token uri
here so since we've already uploaded and
since i've already actually uploaded all
three
what you could do
and what i like to do is just have a
dictionary here so we don't always have
to be pulling from something
so i have a dog
metadata
dictionary it's going to be equal to and
we're going to add those different dogs
in here so saint bernard
this this saint bernard url
we're going to paste it here i've
actually gone ahead like i said and
uploaded this metadata for all three
dogs
so i'm just going to go ahead and copy
paste all three in here
again we're shortcutting a little bit
here but what you could do is you could
save all these metadatas to their own
file and you could just pull from that
file instead of doing kind of this dog
metadata dictionary so in any case
though we're going to do
dog metadata dictionary
of breed
right because dog metadata dictionary of
saint bernard is going to be this which
again
has
our image uri has everything about our
dog and is perfect what we also might
want to do is write some tests around
our set token uri function of course but
i'm just going to move on so
in any case we've done a lot here i'm
actually going to even close down my
ipfs node
and we should be just about ready for
everything
so of course we'll run our brownie
test
we want to make sure that all our unit
tests are working great
which they look like they are working
fantastically but we are ready to
do a full end-to-end manual test here
and you could 100
and i actually highly encourage you to
100 we're just gonna run these scripts
in order and look to see if our stuff
shows up on the openc nft marketplace so
are you guys ready let's do this so make
sure of course your environment
variables are set here make sure that
your metamask
for rink b
has some eth and
has some link and then we can go ahead
and start running some of these scripts
so we'll do brownie
run scripts
advanced collectible deploy and create
network
rink b integration test moment of truth
and perfect a new token has been created
awesome
we can even go grab this address
let's delete all these tabs that we have
opened up
and we'll go to ringpi.etherscan.io
we'll paste it in here
and we can see
contract has been verified even though
we didn't verify it because it matches
some other source code we can see token
counter is one and we can even go to
tokenid to breed of zero see what breed
it is
so it's breed two and it looks like
we're getting a saint bernard again
which is incredibly adorable we can even
go to events here and we can see the
different events since this is verified
we can even see the name of the events
so we have our breed assigned event
and we have our requested collectible
event first is an index topic of token
id and then there's the un8 read
and then we have the bytes32 request id
and the address requester now let's run
our create metadata script here
so we'll do brownie
run scripts
advanced
create
metadata
network rink beam we don't have to run
create collectible since our deploying
crate already does that so now if we run
our create metadata
i've actually already have i actually
since this is the same bernard again i'm
going to go ahead and get this already
exists delete to overwrite
so what i'm going to do is i'm actually
going to even create another one so that
i get a new nft so i am actually going
to run this crate collectible script so
we're going to do brownie
run scripts advanced collectible
create collectible
network rank b
and what this is going to do all it's
going to do is it's going to fund with
some link
which it's going to be a little bit
overkill with the link but that's fine
and then we're going to do advanced
collectible.create collectable
so we're just going to do two
transactions here
perfect collectible has now been created
now i'm going to wait a solid 30 seconds
to have that chainlink vrf respond
and i'm even going to go to the contract
give it a quick refresh look at this
token counter once the chain-link vrf
responds this token counter will then be
2. now that i see a token counter of 2
here that means that it actually has
responded so we can now run
the create metadata script
and we should have
a new metadata file now you have two
collectibles
zero saint bernard already exists
deleted to overwrite create a metadata
file metadata ring b pug so now if we
look in metadata
for rink b we have a saint bernard and
we now have a pug awesome so we're going
to set the token uri of both of these if
i grab this contract and i go to
testnets.openc
open c
i can paste this address in
and i'll get this doggy and then this
random hash here right and we see there
are two
token uris deployed again if they're not
here you might have to refresh but they
don't have the images right because we
haven't set the token uri so we'll go
back look at the advanced collectible
we've deployed and created we've created
another collectible we've created their
metadata now all we have to do is set
the token uri
so brownie run scripts
advanced collectible
set token uri
network rink b
and this script it's going to loop
through
all
of them and actually going to set those
token arrives so we have
setting token uri of 0
so this transaction is doing exactly
that
and it's going to go ahead and say
awesome here's your output and then it's
going to say setting token uri of token
id one and that's that second
transaction and it also gives us an
output to that one as well
so if we've done this correctly
and we hit refresh metadata on this
testnet openc.io
and we do a little refresh here
we can now see our saint bernard which
is fantastic and then if we change
this from 0 to 1 since i've deployed 2
and i refresh this one's metadata and
then refresh the page
we can now see the pug as well
again just keep in mind sometimes the
refreshing metadata does take some time
and you might have to wait up to 20
minutes
but for all intents and purposes we have
just deployed our nfts given them token
uris that aren't around centralized
servers we can now see them on an nft
marketplace like openc
you can let out a big sigh of relief
because you just did something fantastic
that not a lot of other engineers can do
you should be incredibly proud of
yourself at this point let's take a
minute go back over to some of the new
things that we've learned here
when deploying your smart contracts on
chain we all know that those smart
contracts are immutable or unchangeable
but what if i told you that they were
mutable
well technically i wouldn't be correct
however smart contracts actually can
change all the time when people transfer
tokens when people stake in a contract
or really do any type of functionality
those smart contracts have to update
their balances and update their mappings
and update their variables to reflect
this the reason that they're immutable
is that the logic itself never changes
and will be on chain like that forever
so technically yes once they are
deployed they are immutable and this is
actually one of the major benefits of
smart contracts in the first place that
nobody can tamper with or screw with our
smart contracts once we deploy them
however this can be an issue if for
example we want to upgrade our smart
contractor protocol to do more things or
we want to fix some glaring bug or issue
that we have now even though we can't
change the specific code that's been
deployed to an address we can actually
do a lot more than you think we're going
to explain the different methodologies
behind upgrading your smart contracts
and then we're going to show you how to
do it now at first glance you might be
thinking
if you can upgrade your smart contracts
then they're not really immutable then
in a way you'd be right so when
explaining kind of the different
philosophies and patterns that we can
use here we do need to keep in mind the
philosophies and decentralization
implications that each one of these
patterns have as they do all have
different advantages and disadvantages
and yes some of the disadvantages here
are going to affect decentrality so we
need to keep that in mind and this is
why it's so important that before you go
ahead and jump in and start deploying
upgradable smart contracts you
understand the trade-offs we're going to
look at three different ways to upgrade
your smart contracts the not really
upgrading method the social aka my
grading method and then the method that
you're probably here for which is
proxies so let's talk about the not
really upgrading method or the
parameterization method or whatever you
want to call it this is the simplest way
to think about upgrading your smart
contracts and it really isn't upgrading
our smart contracts because we can't
really change the logic of the smart
contract whatever logic that we've
written is there we also can't add new
storage or state variables so this is
really not really upgrading but it is
something to think about upgrades is
just parameterizing everything whatever
logic that we've deployed is there and
that's what we're interacting with this
function means we just have a whole
bunch of setter functions and we can
update certain parameters like maybe we
have a reward parameter that gives out a
token at one percent every year or
something like that maybe we have a
center function that says hey update
that to two percent or update that to
four percent it's just a setter function
that changes some variable now the
advantages here are obviously this is
really simple to implement the
disadvantage is that if you didn't think
of some logic or some functionality the
first time you deployed their smart
contract that's too bad you're stuck
with it you can't update the logic or
really update anything uh with the
parameterization aka not really method
and the other thing you have to think
about is who the admins are who has
access to these setter functions to
these updating functions if it's a
single person
guess what you have a centralized smart
contract now of course you can add a
governance contract to be the admin
contract of your protocol and that would
be a decentralized way of doing this so
just keep that in mind you can do this
method just need a governance protocol
to do so another example of this might
be a contract registry and this is
something actually that early versions
of ave used before you call function you
actually check some contract registry
that is updated as a parameter by
somebody and you get routed to that
contract and you do your call there
again this really doesn't allow us to
have the full functionality of upgrades
here you can argue that this registry is
a mix of one of the later versions but
for all intents and purposes this
doesn't really give us that flexibility
that we want for our upgrades but some
people might even think that upgrading
your smart contract is ruining the
decentrality and one of the things that
makes smart contracts so potent is that
they are immutable and that this is one
of the benefits that they have so there
are some people who think that you
shouldn't add any customization or any
upgradability you should deploy your
contract and then that's it trillabits
has actually argued that if you deploy
your contract knowing that it can't be
changed later you take a little bit
extra time making sure you get
everything right and there are often
less security vulnerabilities because
you're just setting it for getting it
and not looking at it again now if i
were to deploy a smart contract and i
wanted to upgrade it with this
philosophy in mind that hey we got to
keep it immutable we could use the
social yate method to actually upgrade
to new versions the social yet method or
the migration method is just when you
deploy your new contract not connected
to the old contract in any way and by
social convention you tell everybody hey
hey this new contract this new one that
we just deployed yeah this is the real
one now and it's just by convention of
people migrating and over into using
this new one that the upgrade is done
hence my slang name of social yi because
you
yeet the first one out of the way and
move to the second one
i think i'm funny
this has the advantage of truly always
saying hey this is our immutable smart
contract and this is our new one this is
really the truest definition of
immutable because since you give it no
way of being upgraded in place then if
somebody calls that contract in 50 000
years in the future it'll respond
exactly the same another huge
disadvantage here is that you have to
have a totally new contract address
so if you're an erc20 token for example
you have to go convince all the
exchanges to list your new contract
address as the actual address keep in
mind that when we do this we do have to
move the state of the first one over to
the second one so for example if you're
an erc token moving to a new version of
that erc token you do have to have a way
to take all those mappings from the
first contract and move it to the second
one obviously there are ways to do this
since everything is on chain but if you
have a million transfer calls i don't
want to have to write the script that
updates everyone's balance and figures
out what everyone's balance is just so i
can migrate to my new version of the
contract so there is a ton of social
convention work here to do trailer bits
has actually written a fantastic blog on
upgrading from a v1 to a v2 or etc with
this yeet methodology and they give a
lot of steps for moving your storage and
your state variables over to the new
contract so link in the description if
you want to read that now let's get to
our big ticket item so in order to have
a really robust upgrading mentality or
philosophy we need to have some type of
methodology or framework that can update
our state
keep our contract address and allow us
to update any type of logic in our smart
contracts in an easy way which leads us
to our big ticket item the proxies
proxies are the truest form of upgrades
since a user can keep interacting with
the protocols through these proxies and
not even notice that anything changed or
even got updated now these are also the
places where you can screw up the
easiest proxies use a lot of low-level
functionality and the main one being the
delegate call functionality daily gate
call is a low-level function where the
code in the target contract is executed
in the context of the calling contract
and message.sender and message.value
also don't change so you understand what
delegate call means now right great and
in english this means if i delegate call
a function in contract b from contract a
i will do contracts b's logic in
contract a so if contract b has a
function that says hey store this value
in a variable up top i'm going to store
that variable in contract a this is the
powerhouse and this combined with the
fallback function allows us to delegate
all calls through a proxy contract
address to some other contract this
means that i can have one proxy contract
that will have the same address forever
and i can just point and route people to
the correct implementation contract that
has the logic whenever i want to upgrade
i just deploy a new implementation
contract and point my proxy to that new
implementation now whenever a user calls
a function on the proxy contract i'm
going to delegate call it to the new
contract i can just call an admin only
function on my proxy contract let's call
it upgrade or something and i make all
the contract calls go to this new
contract when we're talking about
proxies there are four pieces of
terminology that we want to keep in mind
first is the implementation contract the
implementation contract has all of our
logic and all the pieces of our protocol
whenever we upgrade we actually launch a
brand new implementation contract the
proxy contract proxy points to which
implementation is the correct one and
routes everyone's calls to the correct
implementation contract you can think
the proxy contract sits on top of the
implementations the user the user is
going to be making contracting function
calls through the proxy contract and
then some type of admin the admin is the
one who's going to decide when to
upgrade and which contract to point to
in this scenario the other cool thing
about the proxy and delegate call is
that all my storage variables are going
to be stored in the proxy contract and
not in the implementation contract
this way when i upgrade to a new logic
contract all of my data will stay on the
proxy contract so whenever i want to
update my logic just point to a new
implementation contract if i want to add
a new storage variable or a new type of
storage i just add it in my logic
contract and the proxy contract will
pick it up now using proxies has a
couple of gotchas and we're going to
talk about the gotchas and then we're
going to talk about the different proxy
contract methodologies because yes there
are many proxy contract methodologies as
well and this is why trillabits doesn't
really recommend using upgradable
proxies for your smart contracts because
they're fraught with a lot of these
potential issues not to mention again
you do still have some type of admin
who's going to be upgrading your smart
contracts now if this is a governance
protocol then great you're decentralized
but if this is a single group or entity
then we have a problem
the two biggest gotchas are storage
clashes and function selector clashes
now
what does this mean when we use delegate
call remember we do the logic of
contract b
inside contract a so if contract b says
we need to set value to 2 we go ahead
and set value to 2. but these smart
contracts are actually kind of dumb we
actually set the value of whatever is in
the same storage location on contract a
as contract b so if our contract looks
like this and we have two variables in
contract a we're still going to set the
first storage spot on contract a to the
new value this is really important to
know because this means we can only
append new storage variables in new
implementation contracts and we can't
reorder or change old ones this is
called storage clashing and in the
implementations we're going to talk
about they all address this issue the
next one is called function selector
clashes when we tell our proxies to
delegate call to one of these
implementations it uses what's called a
function selector to find a function the
function selector is a four byte hash of
the function name and the function
signature don't worry about the function
signature for now now it's possible that
a function in the implementation
contract has the same function selector
as an admin function in the proxy
contract which may cause you to do
accidentally a whole bunch of weird
stuff for example in this sample code in
front of you even though these functions
are totally different they actually have
the same function selector so yes we can
run into an issue where some harmless
function like
get price has the same function selector
as upgrade proxy or destroy proxy or
something like that this leads to our
first out of the three implementations
of the proxy contracts this is called
the transparent proxy pattern and this
is actually going to be the pattern that
we're going to be demoing to you today
in this methodology admins are only
allowed to call it admin functions and
they can't call any functions in the
implementation contract and users can
only call functions in the
implementation contract and not any
admin contracts this way you can't ever
accidentally have one of the two
swapping and having a function selector
clash and you run into a big issue where
you call a function you probably
shouldn't have if you're an admin you're
calling admin functions if you're a user
you're calling implementation functions
so if you're an admin and you build some
crazy awesome d5 protocol you better
come up with a new wallet address
because you can't participate the second
type of proxy we're going to talk about
is the universal upgradable proxy or the
ups
this version of upgradable contracts
actually puts all the logic of upgrading
in the implementation itself this way
the solidity compiler will actually kick
out and say hey we got two functions in
here that have the same function
selector this is also advantageous
because we have one less read that we
have to do we no longer have to check in
the proxy contract if someone is an
admin or not this saves on gas of course
and the proxy is also a little bit
smaller because of this the issue is
that if you deploy an implementation
contract without any upgradeable
functionality
you're stuck and it's back to the yeet
method with you and the last pattern or
methodology that we're going to talk
about is the diamond pattern which does
a number of things but one of the
biggest things that it does it actually
allows for multiple implementation
contracts this addresses a couple
different issues for example if your
contract is so big and it doesn't fit
into the one contract maximum size you
can just have multiple contracts through
this multi-implementation method it also
allows you to make more granular
upgrades like you don't have to always
deploy and upgrade your entire smart
contract you can just upgrade little
pieces of it if you've chunked them out
the disadvantages here really only seem
like you have a lot more complicated
code all the proxies mentioned here have
some type of ethereum improvement
proposal and most of them are in the
draft phase there isn't really a
standard here for the proxy that the
whole community has landed on and says
yes
this is great let's do it so for all
these be sure to jump on the discussion
and give your thoughts all right so now
that we know a lot more about upgrades
and how they actually work and some
different methodologies behind them
let's go ahead and learn how to actually
implement some of these strategies and
implement our contract so that we can
upgrade them now there is a brownie
upgrades mix directly in the brownie
mixes organization that if you want to
use you absolutely can once again to do
that it's just brownie
bake upgrades mix and this will have all
the code that we're going to teach you
how to use right now but let's go ahead
and build this up from scratch ourselves
so
we're going to go ahead and run brownie
knit
this of course we're going to create our
new browning project here we're going to
be using the open zeppelin proxy
contracts to actually work with this and
run with this the methodology that we're
going to be working with is the
transparent upgradable proxy now they've
been using the universal upgradable
proxies a little bit more however the
transparent upgradeable proxy is really
fantastic and easy to understand so
that's going to be the one that we're
going to be working with here and these
are the two contracts that we're going
to be importing directly from open
zeppelin so let's get to it we're going
to create a really simple contract that
we can easily tell if it's upgraded or
not
we're going to be using the exact same
ones that open zeppelin actually uses so
let's create a new file and this is
going to be called box.soul we're just
going to have it store and retrieve some
type of value so let's give the spdx
license
identifier
of mit so let's pick our solidity
version
and for this we're actually going to use
0.8.0
oftentimes you're going to have to
quickly pick up new versions of solidity
anyways anyways we're going to do
contract box and we're going to give it
a uint256
private value
we're going to do an event called
value changed
i'm going to give it to you in 256 new
value
give it a function store
uin256
new value
and this is going to be a public
function that anybody can call
and all we're going to do is we're going
to set value
to be new value
and we're going to omit
this value changed
event then we're going to have a
function
retrieve and this will be a public view
and it's just going to return
the ui 256
value return value and this is going to
be our whole contract hopefully you can
understand everything that's going on in
this contract i should spell license
right shouldn't i now we're going to
copy all of this code
and create a new contract called box
v2.sol
we're going to paste it in
and box version 2 is going to be exactly
the same
except we're going to add
one more function called increment
this is going to be a public function
and we're going to set value equals
value plus one
and we're also going to omit
a value changed event
with that new value
now this is going to be really easy for
us to check to see if a contract has
been upgraded or not
if we can call increment
on the same address that we originally
deployed box to then this means that the
contract has been upgraded we shouldn't
be able to call increment
on this box contract but we should be
able to call it on box v2 perfect so
that's all we need to do to get started
now to actually work with the proxies
and the transparent proxy that we're
going to be working with we do need to
add them
to our browning project
so we're going to create a new folder
and we're going to call it transparent
proxy
and in here we're going to add those two
contracts we're going to add one
called proxyadmin.sol
and all we're going to do is we're going
to grab all the code
from the opens up and proxy contract and
paste it right in here
since
since this code is pulling directly from
it it opens up one package we are going
to have to
fiddle with the imports a little bit to
make a match so brownie can actually
compile it
and of course since we're going to be
working with another package we have to
add this dependencies to our browning
config
so
dependancies
open
zeppelin
open
zeppelin hyphen contracts
and for this one we are going to
actually use 4.1.0
then we have to do compiler
soak
remappings
at open
zeppelin
is going to be equal to this dependency
now while we're in here we might as well
do our dot env
so we can get our environment variables
and we'll add our wallet in here
while it's
from key
private
key
we can now just have this be
at open zeppelin
contracts
access
ownable.soul and we don't need to change
this at all because we're actually going
to keep this transparent
upgradableproxy.com
because this
is the second contract that we're
actually going to grab from open
zeppelin
so let's create a new file
to be called transparent
upgradableproxy.soul this exact
text here
and we're going to copy paste this whole
thing from open zeppelin
boom
paste it in here
awesome and then same thing here we just
have to a little reverse engineer this
at open
zeppelin slash contracts slash proxy
erc
1967 erc 1967 proxy and perfect that is
exactly where we are
so great now if we've done this right we
should be able to run a quick
brownie compile
oops i got to change this to box
v2
now let's run a brownie compile
and perfect
looks like we have compiled we've got
some stuff in build great everything's
working correctly so okay so we have our
box here our box v2 and we have our
proxy contracts as well that we can use
to upgrade this box to a new version we
can even look if we go back to proxy of
open zeppelin if we look at our proxy
admin here
we see it has this function upgrade and
call and this calls the upgrade to and
call on the proxy contract if we look in
the transparent proxy this upgrade to
and call calls upgrade to and call which
has been imported actually so we can
actually even go back go back
go to erc 1967 proxy upgrade
look for that again and this is the
function that it's actually going to
call
and it calls this upgrade to function
which calls this set implementation
function
and all we're doing is we're doing
storage slot dot get address slot of
this implementation slot
that value is going to be this new
implementation
all it's doing is it's setting the
implementation slot to being our the new
address that we wanted to use and we can
see now if we look in the proxy contract
the way that it actually works is it has
this fallback function
where it's always going to delegate all
of our calls to whatever the
implementation contract is
this delegate function if we look at him
there's a little bit of low-level
assembly here
and he uses this low-level delegate call
to send any
function call or any call to this
contract to the implementation contract
so this is exactly the function doing
all that delegation all right so now
that we've dug deep into the code let's
actually script this out and turn this
into a script so let's create a new file
and we'll call it zero one deploy box
dot soul and this is gonna be how we're
actually gonna deploy the box so since
this is a brand new script
we're gonna do def
main of course
our account
going to be equal to get account
which
we're going to do from scripts dot
helpful
scripts import
get account
so let's go ahead create a new file
help
full scripts
oops
scripts.pi
and again we're just going to paste in
that getaccount function from our past
helpful scripts
all right our get account script again
so we can just do account equals get
account oh this should be sorry should
be dot pi excuse me
do a quick print
deploying
to
we'll do
network dot show
active
that means we got to do
from
brownie import network and then we'll do
box equals box
dot deploy
from
account
little brackets
here of course since we're going to be
deploying this contract we also have to
import that from brownie and perfect
this alone should just deploy the box
contract right so this means we could do
something like print
box dot
retrieve
and it should be zero right so if we run
brownie run scripts
o1 deploy
it will deploy that
whoops we also got to add our env
we don't have to put anything in here
yet because we're not actually deploying
to a real network
but let's go ahead and run this
i spelt retrieve wrong
it's probably good to
spell things right let's try it again
and great so we get 0 here perfect
that's exactly what we'd expect it's
cool however though if we run
box dot increment this should error out
right
boom exactly it has no attribute
increment so this is what's known as our
implementation contract this box is
implemented it's the implementation
contract
now we have to hook it up to a proxy so
let's first give it a proxy admin and
proxy admins are optional um and it's
also recommended that if you do have a
proxy admin you're and you're going to
use some type of default protocol
sometimes it's great to have your proxy
admin be something like a multi-sig
gnosis safe which is really fantastic
there's going to be a link
in the github for learning how to
actually spin one of those up let's go
ahead and do a proxy admin because
they're really helpful anyways we could
optionally we could just set ourselves
to be the proxy admin but let's set it
to be this this contract
so we'll do proxy admin
equals
proxyadmin.deploy and again this will be
from
account
and since we're using this proxy admin
we're going to import that as well
so if we look at the proxy admin we see
a couple functions here we see like get
proxy implementation which is just going
to return the address of the
implementation
we have get proxy admin
it's going to be us
change proxy admin we have this upgrade
which is just going to call that upgrade
function on the proxy and then we have
upgrade and call upgrading call
changes the implementation to the new
implementation and then calls that
initializer function since we want these
to be proxies you can see here that we
don't have a constructor
this is intentional instead we could
have some type of initializer
function for example maybe we want to
have this store be our constructor
instead of having a constructor what we
do is we call what's called our
initializer function the instant we
deploy this contract for the demo here
we're just not going to have an
initializer anyways so now we have this
proxy admin we have the implementation
contract we have the proxy admin let's
now hook them up to the actual proxy
first thing that we need to do actually
is we need to
encode the initializer function if we
wanted store to be our initializer
function like i said we could do
something like ini shi al
lizer
equals
box.store comma one and this would be
our initializer box.store combined with
one
what we then have to do is we'd have to
encode this for our proxy if we look at
our transparent upgradable proxy if we
look at the constructor
we have address logic address admin and
data here
the logic is that implementation right
this is going to be the address of our
box the admin is going to be ourselves
or in our case it's going to be that
proxy admin contract
and then data is going to be
that initializer function if we go into
the erc
721 proxy
contract
should go back to proxy erc
1967 upgrade
and we look at this as one's constructor
we can see that this data bit here
once this is built with this constructor
it's immediately going to call this
upgrade to and call so it's going to
call this this initializer if we go to
upgrade to and call if we go back to
this upgrade contract we can see this
upgrade to and call it's going to call
this address dot function delegate call
new implementation data and this is how
it actually
calls that initializer function we have
to actually encode this
into bytes so we have to say box.store
is the is the function a call
and then one is going to be the first
parameter right if this is what we'd
want to do
so we do box
encoded
initially
function
equals encode
function data and this is where it gets
a little bit tricky
but i usually have this encode function
data once again in my helpful scripts
so we'll do quick def encode function
data
and it's going to take
an init
which we're going to start off as none
and then any number of arguments after
that so again this could be like
you know
initializer equals box.store
and then the arguments could be you know
one two three four
five etc or whatever right for us we
only have one variable that can be put
into store but this is how you would do
it and to do this brownie actually has a
built-in function that can actually do
this we just return initializer dot and
code
input
star args
and that's all we'd have to do however
there is a bit of an issue when the
length of the args is zero so i've
already hacked away at it for you guys
so we're just gonna do if
the length of the args
is zero or we're not using an
initializer
then we're going to return
s utils dot two bytes
x string
equals ox
and we do have to import f util
import
at utils and of course we'd have to pip
install it with pip
install
ethertails so i know i kind of rushed
through that but basically what we're
doing like i said
is we're encoding this into bytes so
that our smart contracts actually know
what function to call
so we're just encoding it that's all
we're doing and if it's blank or there's
no initializer we're going to return an
empty hex string and our smart contract
will understand ah okay arguments are
blank here perfect i've got a nice doc
string in the upgrades mix that explains
this even better i'm even just going to
paste it in here for now if you'd like
to pause and read this a little bit more
to
kind of get the full depth of what this
function is really doing feel free to do
that this is a little bit lower level
solidity and evm stuff that we're
getting into here but it can be good to
know anyways
okay great so now that we have this we
could go ahead and run box encoded
initializer function equals encode
function data
which we would import from our helpful
scripts and this is what we use when we
call the constructor for our transparent
upgradable proxy
i'm just going to have it be blank for
now but feel free to fiddle around and
try to actually use an initializer after
we run through this demo so this box
encoded initializer function is going to
be blank we're saying hey
don't use an initializer and that's
totally fine
if we were to add some stuff to here we
would say hey use an initializer so now
we can actually deploy this transparent
upgradable proxy if we open this up with
the constructor we can see
what we need here
so
we're going to say proxy
equals
transparent
upgrade able
proxy.deploy
of course
import this from brownie
and what are those
variables that we need okay we're gonna
need the address the logic this is gonna
be our implementation contract address
so we just say box.address which is our
because we've already deployed this
which is great
then we're going to need our admin which
we could just say is us but we're going
to use the proxy admin
dot address and then last we need that
function selector we need that encoded
function call which for us is just blank
but we still need that
so
box encoded initializer function and
then we have to add from
account of course and i've also noticed
that sometimes it's helpful to add some
type of gas limit
so i'll even add a gas limit
of one
one two three one two three that's six
zeros there but sometimes you might be
fine but uh
with the proxies they they sometimes
have a hard time figuring out the gas
limit so i've just manually put it in
here you can if you want to it might
work fine without it and then great
let's do a quick print function we'll
print
f
proxy deployed to
proxy
you can now upgrade to v2
now what we can do is on the proxy's
address we can call functions so
typically right if we wanted to call a
function on this box contract we do box
dot you know retrieve or however you
spell it box.store let's just do box
store right you'd call it like this
however we want to actually call these
on the proxies right because box this
box contracts address this box contract
is always going to be the same address
and can't change
the proxy code can change we want to
always call these functions to the proxy
and not to the box here right so the way
we do that is we can do proxy box
equals
contract dot from
abi
we'll call it box
on the proxy.address
box.abi
and of course we'll
import this from brownie
what we're doing here
is we're assigning
this proxy address the abi
of the box contract and this is going to
work because the proxy is going to
delegate all of its calls to the box
contract
typically if you put an abi on top of an
address that doesn't have those
functions that the api defines it would
just error
right but the proxy is actually going to
delegate all those calls to the box
so we could actually go ahead and try
something like print
proxybox dot
retrieve hopefully that's about that
right and even though
we're using the proxy address here we
are going to delegate the call
to
box so let's go ahead and run this so
we'll do brownie run scripts
deploy box it's going to deploy the box
it's going to deploy the admin it's
going to encode that initializer
function which we've set to nothing then
it's going to deploy our transparent
upgradable proxy and then it's going to
call
retrieve
on the transparent upgradable proxy
instead of our box so let's do this
and perfect we did it right it's
returning zero here that's awesome what
we could also do is we could also do
proxybox.store
one
and then we'll call retrieve we'll see
what happens here
whoops it's yelling at me because i got
to do
from
account
now let's go ahead and run it
and perfect see so after we stored on
the proxy box on this proxy
we're able to retrieve the value there
so this is fantastic all right now that
we've deployed it let's learn how to
upgrade it we're going to change this to
deploy
and upgrade
dot pi and we're just going to do
everything in here so now that
everything's deployed let's go ahead and
now upgrade this so so now we can always
point to this proxy box address and it's
going to be the most recent upgrade it's
always going to have the code that we
want it to have so let's go ahead and
upgrade from box that doesn't have that
increment to box v2 that does indeed
have this increment function so let's
try this out so first thing we need to
do is we actually need to deploy that
box v2
so we'll do box v2
equals box
b2
dot deploy
we'll save from
account
and we'll leave it like that of course
we're going to have to import box v2
from brownie
and right now actually let's even do
proxy box
increment
if we call boxy proc
proxy box that increments from account
this should error right it shouldn't be
able to call this increment function
because that doesn't exist
oh and then we also change the name of
the script sorry
this is actually going to be
deploy and upgrade
and perfect we see it actually errors
out here it says hey box object doesn't
have this increment function you're
crazy i don't know what you're talking
about
well good that's what we want to do
so let's delete that line
box v2 and we'll even do a quick little
upgrade here
now all we need to do is call
an upgrade function now basically all we
have to do is call this upgrade to
function right but depending on if we've
added a proxy admin contract if we're
using initializer function there might
be a couple of of different ways to go
about this so i like to just wrap
everything up into its own upgrade
function you'll see what i mean in just
a second so
what i like to do again we're going to
pop into our helpful scripts and we're
going to create a new one called upgrade
now for parameters in here of course
we're going to take some type of account
so that we have something to account
to deploy from
we're going to use the proxy which is
again going to be that proxy contract
which is going to be our proxy contract
here we're going to need a new
implementation
address we're gonna need the proxy admin
contract
which could be none for us we're gonna
have one but it could be none and then
we're gonna have an
initializer
which also could be none
and then we're going to have the args
for the initializer which also could be
known again this star
is a special thing in python which says
any number of arguments
will just get stored into this list
called args and perfect this is going to
be our function that's just going to
take care of everything for us so first
thing let's check to see if there is a
proxy admin contract
so we'll say if
there is a proxy admin contract
then we want to check to see if there is
an initializer
what we're going to do is we're first
going to want to encode that function
data of course so we'll say encoded
function call
equals and code
function data
with the initializer
and those star args
this is going to be the encoded
initializer function here
then all we have to do and actually
let's do start with a blank transaction
equals none
we'll say
transaction
equals
proxy admin contract since we're using
one of these proxy admin contracts since
we've detected one
dot
upgrade and call since we also have an
initializer
we're going to pass the
proxy.address
new implementation address
and the encoded function call and then
of course
from
account
so this upgrade and call if we look in
that proxy admin
there's this upgrading call function
right on the proxy admin and it just
calls upgrade to and call of the proxy
contract
so hopefully don't don't let this bog
you down a little bit that there's kind
of a lot of mix and matching going on
but this is what's going on
i'm sorry this is encoded function call
not encoded function data
great now if they don't have an
initializer
well what do we do well we don't need to
encode any function call here we need to
say
transaction
equals
that proxy admin contract
dot upgrade
so it has an upgrading call it also just
has a regular old upgrade so we'll just
call upgrade
and we'll give it the proxy.address
the new implementation address
and then
from
account
now if it doesn't have a proxy admin
contract this means that the admin is
just going to be a regular old wallet
well what do we do then well first
check to see if it has an initializer
still
and if it does we need again
to encode that function call we can just
copy and paste that there and then once
that's encoded we can just call directly
off the proxy contract we're going to
call exactly what the proxy admin
contract is calling which can be
proxy.upgrade
to
and call
we're going to give it the new
implementation address
the encoded
function call
and then from
account
and let's wrap this all up in a big else
so if proxy admin contract do this stuff
else do this stuff
if initializer do that otherwise we can
just do
transaction equals
proxy dot
upgrade 2 and we just add that new
implementation address
from
account
and then we'll finally return
transaction
so i know that there's a lot here but
we're really just making this upgrade
function really general we could always
just know okay if we we we're going to
use a proxy admin let's just do it like
this okay no we're not going to use a
proxy admin we're also not going to use
an initializer great it would just look
like this but this is essentially all
that we have to do so now that we now
that we have our upgrade function
we can go ahead and use it here
so we need to give it an account a proxy
a new implementation address
so we'll say account so we'll say
upgrade
transaction equals upgrade account
we need a proxy and a new implementation
address we're going to give it the proxy
and we're going to give it
box
v2.address for that new address
we do have a proxy admin contract
so we'll say proxy
admin
contract equals
proxy admin and we don't have an
initializer so we can leave that part
blank
of course we need to import this upgrade
function from our helpful scripts
and this is all that we need so now we
can do print
proxy has been upgraded and what we
could do now is we can do proxy box
equals contract dot
from abi
we'll call it box v2
we'll give it the proxy.address
box v2.abi
and now we should be able to call
proxybox.increment
from account and then we can print
proxy box
dot re
retrieve
and this should now be one and what
we'll actually see is that this will
return two
why does it return two
well in our original proxy box we stored
one so it started with one we then
upgraded to this new contract and then
let's actually just do a
wait of course
we upgraded to a new contract
right here
however the storage of that contract
stayed in the proxy so that one stayed
in the proxy so even though we upgraded
the contract
there's still one stored at the location
in storage so then when we call
increment now and then we call retrieve
it's gonna go from one to two so let's
go ahead and run this
brownie run scripts
deploy an upgrade enter
and boom that is exactly what we see
output here this is an incredibly
incredibly powerful and advanced feature
and if you've gotten to this point you
are on the border of being one of the
most powerful smart contract engineers
on the planet huge congratulations for
getting this far but we're not quite
done we of course need to write some
tests because that is what's going to
make sure our project always stays in
sync and always stays up to date so
let's write a couple of tests here so
let's create a new file
we'll call test
box proxy dot pi
and for this we're really just going to
test to see that our contracts work
we're going to see that this box
actually is going to work correctly so
let's create a new test
def
proxy
delegates calls
so we're going to make sure that we
actually can delegate calls to our
contract we're going to say account
equals
get account
which means we have to do from
scripts.helpfulscripts
import get account
then we're gonna do
box
equals
box.deploy
of course this is going to be from
account
since we're using box we're going to do
from brownie import
box
we're going to do this proxy admin so
we're going to say proxy admin
equals proxyadmin.deploy
of course from
account
let's import proxy admin from brownie
all right so now we'll do the box
encoded
initializer function
or whatever we call to perform this is
going to be that encode
function data which
my vs code actually automatically
imported thanks vs code
and again we're leaving it blank
because we're not actually going to have
a store there and then we're just going
to go ahead and run that deployment so
we're going to say proxy equals
transparent
upgrade
proxy
and we're going to grab this from
brownie dot deploy
say again the box.address
proxyadmin.address
box encoded initializer function
i'm going to say from
account and then we'll give this a gas
limit
of
two three one two three
now we're gonna put the abi on top of
this proxy so we're gonna say proxy box
equals
contract dot from abi
we're gonna name it box
this is going to be with the
proxy.address
[Music]
and the box.api
of course we're going to need to
import contract from brownie
and okay so now we can assert
proxybox
dot retrieve
if i spot that right is equal to zero
then we're going to do proxy box
that's store
we'll do one
and this will be from account
and then we're going to sir again
this proxybox.retrieve
should now equal 1.
so we're using this proxy contract
we've slapped the abi on top of it and
this should work
so we're just testing to see that our
proxy is working correctly
so we can go ahead and test this then
with
rounding test
and beautiful it passed
now let's go ahead and create a new
script for testing the upgrades create a
new file called test
box v2 upgrades
dot pi
and let's do it
called def
test
proxy upgrades
so account
it's gonna be equal to get account
hopefully at this point you're getting
pretty good at writing these these tests
from
scripts.helpfulscripts
imports
and of course we want to add this init
dot pi just in case you forgot so now
we're going to import get
account perfect so we have our account
here now as you can see we're doing a
lot of this box equals box dot deploy
deploy the proxy admin it would probably
make sense in one of your scripts to
just write a deploy three
to write a function called like deploy
all or something like that
so again if you guys want to learn more
if you want to improve upon this i would
highly recommend you go back and you
make some of those improvements to to
really modularize this up but for the
time being let's just keep going
so box.deploy
from
account
and since we're doing this we're going
to do from
brownie import box
say proxy
admin
equals
proxyadmin.deploy
this will also be from
[Music]
account
comma proxy admin
we're going to get those initializer
functions so we'll say box
encoded
initializer
function
equals encode
function data which we're going to grab
from our helpful scripts as well
and then we're going to do the proxy
again
box equals transparent up
gradable proxy
that deploy
we've got to import this from brownie as
well oops not twice though
deploy
it's going to have the box that address
proxy admin dot address
box encoded initializer function
from account
gas limit
one two three one two three
all right
so we have the proxy deployed we've
already tested that this proxy works in
this test box proxy so we're not going
to go ahead and test that again
what we're going to do instead now is
now we're going to deploy
box v2
and we're going to update the proxy and
make sure that everything still works
so we're going to do box v2
equals box v2
dot deploy
it's going to be from
[Music]
account of course
now we're going to say proxy
box
equals
contract.from api
box v2
proxy.address
v2.abi
and we're going to grab
both this
and this from brownie
and what we're going to try to do
is slapping this abi
onto this proxy address we're going to
try to call a function only box v2 can
call
however we know that
like what we tested before it actually
should revert
so we can actually check for reverts by
importing
pi test
and we can say
with pi test
dot
raises
and i know that
this is a brownie exception i know what
type of exception this is it's an
exceptions dot virtual machine error
you can figure out what type of error
this is by
just just running it and getting the
error so this is actually from brownie
this exceptions thing so we're going to
actually also import exceptions from
brownie we're going to say
proxybox.increment
from
count
and i saved and everything sorry got
formatted here but calling
proxybox.increment should throw this
exceptions.virtual machine error so this
test will pass if this throws an error
and that's how we test that so we want
this to throw an error the first time we
call it then we're going to upgrade and
then we'll call it again and it'll
actually work
now we're going to call upgrade
on account
proxy
box v2
proxyadmin
contract equals
proxy admin
we're going to need to grab upgrade from
our helpful scripts and now we should
actually be able to
call increment with our proxy box
so first we'll do a quick assert
proxy box dot
retrieve equals zero
then we'll do proxy proxybox.increment
from
account
and then we'll assert
proxybox dot retrieve
is
one so we're deploying our box we're
deploying our proxy and everything
around it
then we're deploying our v2
implementation
we're trying to call increment which
won't work we then upgrade our proxy to
this new address
and then we can go ahead
and call
increment and it should actually
increment our box here
so let's go ahead and run this test
brownie run test
excuse me
ronnie test dash k
grab this paste it in
and we've done it our tests are working
correctly so we know that our box is
working correctly
awesome great job like i said this is an
incredibly incredibly powerful feature
to be able to do these upgrades with
these there comes a lot of risk at least
in the form of centralization risk if
you're the only wallet that controls the
proxy that means your application is
centralized full stop so if you're going
to deploy anything with proxies to
mainnet
absolutely absolutely be sure to get it
audited beforehand
now before we close this project up
let's actually deploy this to an actual
test snap
so that we can see everything that goes
on when we call this deploy and upgrade
let's go ahead and do it
so
let's pop into our emv file
and let's paste the variables that we
have in here we need the private key web
three inferior project id the ether scan
token
awesome
let's even
let's even publish the source of all
these contracts so that we can see them
on etherscan
so for box we'll do a little comma here
we'll say publish
source equals true
i'm just going to copy this comma to
publish source equals true
and paste it on all of my deployments
over source equals true
publish source equals true on the
on the admin
on the initial transparent upgradable
proxy
on the box v2 deployment
and that's it
i've got my ether scan token my web 3
and fira my private key my brownie
config is indeed pulling from the
private key my env has env let's check
to see my wallet
we have some rink being here perfect
let's do this
brownie run scripts
deploy and upgrade
network
rink
all right so it looks like a couple of
our contracts weren't able to actually
verify there are a couple bugs being
worked out with some of the verification
so we're going to ignore the ones that
weren't able to be verified here but
let's go ahead grab these addresses pop
them onto the rink etherscan and see
what just happened
this is our box implementation let's
grab this address let's paste it into
the rinkby testnet ether scan awesome
this is exactly what we have contract
has been verified this is exactly the
code that we have here
and we can see all we have is a contract
creation and this is exactly correct
because when we call
the store function on this it's actually
going to get stored we never actually
called any functions directly on this
contract all we did was deploy it which
makes perfect sense let's go check out
this proxy admin now
this second address
the second counter that we deployed
sadly this one didn't get
verified however we can see we did
indeed call this upgrade function at
some point
which makes a lot of sense
if we look at our script
proxy admin
in our upgrade code since we did have a
proxy admin contract we did call that
upgrade function
perfect makes sense now let's go to this
transparent upgradable proxy this is
going to be the most interesting one out
of all of our
applications
interestingly enough we look at this
contract we can see store in increment
both have been called on this contract
not on the box because again this is the
proxy that we're going to call all the
functions on to make our contracts
upgradable internal transactions are
calls that another smart contract made
to this transaction and if we look at a
couple of these
we can see if we click more
we had increment called from another
contract which makes sense we had
upgrade called from the proxy admin
and then we also of course we had store
called from another contract and if we
verified this we would be able to see
etherscan recognize this as a proxy
contract as well hopefully when you work
with this you'll be able to verify it as
well but if not not a big deal you can
always just manually do it later
yourself so this was an incredibly
powerful project that we just did here
and that we worked on and all right
maybe take a nap maybe go for a walk get
some food get a drink because we are on
to our last coding project now i do want
to say that this project is considered a
bonus because we're going to be going
very quickly over the front end pieces
we're going to take all the building
blocks that we've learned and build an
amazing full stack application gear up
get ready let's jump into this bonus
project and then after we finish this up
we're going to close everything out with
a final quick section about security the
future and and thank you for joining
this course so let's do this last one
all right now we are moving on to our
final project this is going to be the
most advanced products and combine all
the knowledge that we've learned so far
into one project
then we're additionally going to put a
front end or a user interface onto this
project when we build our own
applications we're going to need a way
for non-devs to actually interact with
it in a meaningful way so now this isn't
a front end or react tutorial course
although we will be explaining some of
the choices that we've made and how to
actually do them you should be able to
follow along fine even if you don't have
any front end experience here if you're
looking for a full front end tutorial
free code camp has some amazing videos
that you can absolutely try out all
right welcome back everybody and now
we're going to be embarking on the most
exciting the most end to end we're going
to take everything that we've learned
and wrap it all together in this single
last application here and we're also
going to be learning about front end
development we're going to be building a
front end on top of our application on
top of our contracts here now this isn't
a front end tutorial however free code
camp has some wonderful wonderful react
tutorials we're going to be teaching you
guys just enough so that you can go
ahead jump in and build your own simple
but also kind of nice looking front ends
on top of whatever contracts that you
have
for those of you who want users to
actually interact with your applications
and interact with your contracts
building a usable front end is a really
important piece so let's take a quick
walkthrough of what this application is
going to look like so here is our our
front end here and what this application
is going to allow users to do is it's
going to allow users to stake or deposit
their tokens into what's called our
token farm contract once they have some
token deposited that's when you can kind
of go get creative with what you want
those tokens to do
you could use it as staking in some
governance you could use it to you could
go ahead and invest it in something like
ave or another d5 protocol to gain
interest you could build a yield
aggregator there's a ton a ton of
different features that you can actually
do once you have users stake their
tokens and here's how they would do it
on their ui side so we have this little
button here which we go ahead and click
connect on metamask is going to pop up
and we're automatically going to sign in
that's going to connect our meta mask to
this user interface now so if i look at
my meta mask i'm on the coven test
network we can see that i am indeed
connected now what i can do
is i can now stake some of my tokens
into this contract we currently have
three different types of tokens that
this platform allows you to stake
wrapped ether
fiu which is mimicking die on the test
network and our dap token this dap token
is going to be the reward token that our
platform gives users as an incentive for
staking on our platform once we stake we
can actually then unstake and that's
really it
so we'll go ahead and stake maybe we'll
stake 10 dap we'll hit stake metamask
will pop up this is the approve function
this first approved function that gets
called we get a really nice little
waiting
bar here and once it's been approved we
get a notification saying the transfer's
unapproved we then go ahead and we'll
confirm staking we'll get this little
loading bar while it's being staked and
we'll see that pop-up that says tokens
staked successfully
now if we go to the token farm contract
we can see that we have 10 of this dap
token state
we can also unstake it the other thing
that we can do is as admins of this
wallet we can actually issue a reward
to our users based on how much they've
staked so you see right now we have 95
dap token
we have 10 dap tokens staked on the back
end i'm going to run an issue token
script it's going to send all users that
have some stake a little bit of a dap
token reward now you can see it's been
updated
and we have we've been given a little
bit of dap token that resembles the
amount of dap token that we have staked
the way that we figure out the value of
all of our different tokens is using of
course chaining price feeds we can then
of course unstake everything
and we see tokens unstaked successfully
and that's it and this is what we're
going to build now we aren't going to go
over the unstaking portion of the front
end application here right here's what
it would look like if you were to go
ahead and finish building out the front
end yourself there is a full repository
with the entire front end with this
unstaking piece but for simplicity we're
just going to skip over this unstaking
bit so let's go ahead and get started
i'm going to go ahead and make a new
directory called defy
stake
yield
brownie
and then i'm going to open
this up in a new text editor now the
first thing of course that we want to
work with
is going to be our contract so we're in
here remember
always start with brownie init
or you can start with the chain link mix
i'm just going to go ahead and start
with brownie unit and perfect here is
our setup all right first thing we're
going to do is we're going to make our
app token dot sol
this is going to be the token that we're
going to give out to users who are
staking on our platform this is our
reward token you might have heard of
yield farming or liquidity mining this
is our token that allows users to
actually engage and participate in that
and this is just a regular old erc20 so
you guys already know we've done this
before and for this one we're even going
to use the latest and greatest in
solidity remember i said that you're
going to have to get really good at
bouncing around between solidity
versions so for this one we're going to
do everything in 0.8
so let's go ahead and do that so we're
going to do pragma
solidity
0.8.0
and we're going to do this the exact
same way we made our other erc20 token
we're going to go ahead and use open
zeppelin again we can even just copy
paste the import from their
documentation or we can just write it
out
import
at open zeppelin
contracts slash token
erc20
erc20.sol
and you guessed it because we're using
this at opens up on syntax we're gonna
make a new file
routing config.yaml
we're gonna make some dependencies
we'll do open
zeppelin slash open
[Music]
zeppelin
contracts
this time we're going to actually use
version 4 of these
at 4.2.0
and again you can find out everything
about this package by going to opens up
when slash opens up on contracts on
github and then compiler
sulk
remappings
at open
zeppelin
equals
this part right here
paste it in okay
great
then what we can do
we can go back to our dap token and just
do some basic erc20 bits here
so do contract
dap token
is erc20
and we'll give it our constructor
public
erc20
we'll call it
depth token and we'll give it a symbol
of dep
and we'll give it an initial supply as
well
so we'll call the mint function
and we'll set the
meshes.sender as the owner give it an
initial supply of one million which will
be one one two three one two three plus
those eighteen zeros so one two three
four five six seven eight nine ten one
two three four five six seven eight
and now that we have our first contract
we can try to compile it
ronnie
compile
and looks like it worked great
now we're gonna go on and to create our
more interesting contract
our token farm
we can even take a quick second and
figure out what we want this to be able
to do
well we want to be able to stake tokens
tokens
issue tokens this is going to be issuing
those token rewards
we're probably going to want to add
allowed
tokens to add more tokens to be
allowed to be staked on our contract
and we're probably going to want some
type of
get f value function where we can
actually get the value of the underlying
stake tokens in the platform with that
in mind let's move on so
you know the drill pragma solidity
carrots 0.8.0
and we're going to be here for a while
so i'm going to close those out
and this will be our contract
token farm
contract token farm oh and let's not
forget
our s
pdx
license
identifier
of mit well let's go ahead and start
with the staking of the tokens right
because that's going to be the most
important piece of our application so
we're going to do function
state tokens
you'll probably want to stake
an amount of token
and they'll probably want to stake
a certain address of the token
so
some amount of some token
now there's a couple things we need to
keep in mind here what tokens can they
stake
how much
can they stake
so these are our first two questions
for our application we're just going to
say you can stake any amount greater
than zero so we can even add that we'll
do require
amount
is greater than zero
and if it's not we'll just say
amount
must be more
than zero
since we're using version 8 we don't
have to worry about anything to do with
safe math which is awesome so we can
just go ahead and do stuff like this we
now we only want certain specific tokens
to be staked on our platform so we could
say require token
is allowed
or something to this effect so we might
have to actually create a token is
allowed function
so let's go ahead and create that
function
token is
allowed
it'll take
some token address make it a public
function and it'll return
a boolean it'll return true if that
token's allowed or false if it's not
allowed so how do we know if a token is
actually allowed we probably want some
list or some mapping of these tokens and
whether or not they're allowed after all
we've learned you'll probably learn that
there definitely are some trade-offs
between lists and mappings here for
simplicity's sake we're just going to
stick with a list for now
so we're going to create an address
array
we'll make it public
called allowed token
and this will just be a list of all the
different allowed tokens
for our token is allowed function we'll
just loop through this list and see if
that token is in there
so we'll do a for loop
four
uint256
allowed tokens index
equals zero
allowed tokens index
is less than
[Music]
allowed tokens dot length
allowed tokens index plus plus
so we're going to loop through this list
and we're just going to say if
allowed tokens
of allow token index
equals equals
this token
then we're going to return
true
otherwise if we get through this whole
for loop and we don't find this token in
here we're just going to return false
now we have a way to check to see if
allowed tokens are there let's actually
write a function to add aloud tokens
so we can do function
add aloud tokens
address token
public function and we'll do allowed
tokens and we'll just push
it onto that array now adding allowed
tokens is probably something we only
want the admin wallet or the owner of
this contract to do so we'll add only
owner
as a modifier to this function and we'll
make this token farm ownable is
ownable and we'll import from open
zeppelin here too
import at open
zeppelin
contracts slash access
ownable.soul
let's do a quick compile
great things are being compiled
fantastically now that we have a little
bit of functionality here now might be a
good time to actually go ahead and start
writing some tests if you want to since
i know that we're going to change the
constructor a little bit and we're going
to change a little bit of how this is
actually formatted i'm just going to
keep going but now might be a great time
should i start writing some tests for my
application
you know we're going to do those tests
later on anyways though all right great
but in any case now that we have these
two functions we can go ahead and
actually start checking to see if the
tokens that these stakers are going to
stake is actually allowed
so what we can do now is we're going to
add this require statement in we can
require token
is allowed
of token
otherwise we'll just say token
is currently
not allowed
and perfect now we have two required
statements that answer these questions
what tokens can they stake
and how much can they stake so now all
we have to do is we just have to call
the
transfer from function on the erc20
remember erc20 remember erc20s have
these two transfer type functions they
have transfer and they also have
transfer from
transfer only works if it's being called
from the wallet who owns the tokens if
we don't own the token we have to do
transfer from and they have to call
approve first so we're going to call the
transfer from so we're going to call the
transfer from function on the erc20
since our token farm contract isn't the
one that owns the erc20 we also have to
we also have to have the avi to actually
call this transfer from function so
we're going to need
the ierc20 interface we could go ahead
and pop it in here we could also make it
near c20 contract we could also just
grab it from openzep1
so we'll do import
at open
zeppelin contracts slash token slash
erc20
ierc20.sol
we're using the interface here because
we don't need the whole contract anyways
let's now wrap ier c20 let's wrap this
token address
as an erc20 token so now we have the abi
via this interface and the address
and we'll call that transfer
from
from the message.sender
and we'll send it
to this token farm contract so from
whoever calls stake tokens
to this token farm contract
and we'll send the amount
and perfect now we just need to keep
track of how much of these tokens
they've actually sent us so we're going
to want to create
some type of mapping here
and this mapping is going to map token
address
to
sticker address
to
the amount this way we can keep track of
how much of each token each staker has
staked
so it's a mapping per token per staker
per amount
so we'll just call this
mapping of that token address
which is going to get mapped to
another mapping
of those
user addresses which then gets mapped to
a uni-256 so we're mapping the token
address to the staker address to the
amount we'll make this a public mapping
we'll call it
staking balance now that we have this
mapping
in our state token function
what we can do is we can say staking
balance of this token
from message.sender
is now going to equal whatever balance
that they had before plus
the amount
all right this is great now we have a
way for users to stake different tokens
that we've actually allowed them to
stake on our platform awesome work so
what do we want them to be able to do
next we want them to unstate tokens we
want to be able to issue some reward we
want to be able to get the eth value
based on that reward typically you might
want to do this unstake tokens bit first
however i know that we're actually going
to need some additional functionality in
our state tokens function for us to
actually issue tokens properly so let's
just go ahead and do this issue tokens
bit remember this issue tokens is a
reward we're giving to the users who use
our platform so we want to issue some
tokens based off the value
of the underlying tokens that they've
given us
so for example
maybe
they've deposited 100 eth and we want to
do
a ratio of one to one
for every one each
we give one depth token
that's pretty easy for us to figure out
however let's say they have 50 each and
50 die staked and we want to give a
reward of
one dap
one dapp token
per one die
well then we'd have to convert all of
our eath into die so we know that
conversion ratio for the dap token so
that's the problem that we're going to
work on now let's create this function
called issue tokens
and this
is going to be a function only callable
again by the owner
or the admin of this contract so how do
we actually go ahead and issue tokens
here well the first thought would be to
loop through a list of all the stakers
that we have but right now we don't have
a list of stakers what do we have we
have a mapping of stakers and we have a
list of allowed tokens well we're
probably going to need to have a list of
stakers so we'll do an address array
because again we can't loop through a
mapping so we'll do an address array
we'll make it public
called stakers
this is just a list of all the different
stakers on our platform now when
somebody stakes a token
we're going to have to update this
list
we want to make sure they're only added
if they're not already on the list
so in order for us to do this we should
get an idea of how many unique tokens a
user actually has
so i'm going to create a function called
update
unique
tokens staked
with message.sender
and the token
and what this function is going to do
it's going to get a good idea of how
many unique tokens a user has
and if a user has one unique token we
can add them to the list
if they have more than one we know that
they've already been added to the list
so we don't need to add them there
so let's create this
function update unique token state
we'll have it input an address
user
and an address
token
and we'll make this
an internal function
so that only this contract can call this
function and what we'll say is if
staking balance
let's even do a little underscores here
of token
of user
is less than or equal to zero
we're going to update some unique tokens
staked mapping so we'll say unique token
staked
of the user
it's going to equal
the unique token staker of the user
plus one and since we have this new
mapping called unique token staked we'll
make that as well
so we'll do a mapping
of an address
to
the un256
public called unique tokens state so
this way we know how many different
tokens each one of these addresses
actually has staked now that we have a
better idea of the unique tokens each
one of these users has staked what we
can do
is we can figure out whether or not we
want to push them onto this stakers list
if they're already on there we don't
want to push them on there if they're
not on there then we do want to push
them on there so we can just do is say
if unique token staked
of
message.sender
it's equal to one if they have one
unique token state if this is their
first unique token we're going to add
them to that stakers list so we'll say
stakers.push
message.sender and this is going to be
our completed sake tokens function here
so we had to add this little extra
functionality between the unique tokens
to figure out how to actually issue some
reward for them but now that we have
this list and it's going to get updated
here
and it will also get updated when we
unstake
what we can do now is just loop through
this list of stakers so we can say 4
unit 256
staker's index equals zero
stakers index is less than stakers dot
length
stakers index
plus plus
and now we're going to issue some of
these tokens here so we're going to say
the address
recipient
equals stickers
stakers index so one at a time we're
going to loop through grab these
recipients and then we're going to send
them
a token reward
based on their total
value locked
so we got to do a couple things here we
have to send them a token reward we have
to figure out how to actually send them
this token and then we also have to get
their total value locked
so let's do this to send them a token
reward this is going to be this dap
token that we created in the beginning
this is going to be our dap token so
right when we deploy this contract we
need to know what a reward token is
actually going to be so we can do
right at the top and then i'm actually
going to
i'm actually just going to move this
array
up here so that they're all kind of
nicely together what we need to do
is we need to create a constructor
right when we deploy this contract we
need to know what is the address of the
dap token what's the address of the
reward token that we're going to give
out
so we can say constructor it will be
passed an address of the dap token
address
this will be a public function
and
we'll store this dap token as a global
variable
so we can say
ierc20 since we're already importing it
here
public
dap token
what we can do now is set depth token
equals ierc20
underscore
dap token address so now we have this
dap token with its associated address
and what we can do now
is call functions on it for example we
can call
dap token
dot transfer
we can call transfer here because our
token farm contract is going to be the
contract that actually holds all these
dap tokens and we're going to send this
token to
the recipient of course
but how much are we going to send right
how much this of this token
are we going to send to them well we
need some function to get the total
value so we're going to say u and 256
use your total value
equals
some function
right and we can go ahead and define
that right now we'll call this function
get user total value right or get
recipient total value or whatever you
want to say
so we'll pop recipient in here and let's
go ahead and create this function so
we'll call function get user
total
value
address
user
and this is where we do a lot of looping
right we're gonna we gotta find out how
much each of these tokens actually has
now what a lot of protocols do instead
of actually them sending and them
issuing the tokens is they actually just
have some internal method that allows
people to go and claim their tokens
right you've probably seen that before
people claiming airdrops that's because
it's a lot more gas efficient to have
users claim the airdropped instead
of the application actually issuing the
tokens right it's going to be very gas
expensive to do looping through all
these addresses and checking all these
addresses right we're going to do it
though because we are a wonderful
amazing protocol and we want to give our
users the best experience but in any
case this is going to be a public view
function
that will return
a uin256 right because we want to return
this total value to our issue tokens
function up here so how do we actually
get started here well let's create
a unit 256
total value
and we'll set it off to start it to be
zero here and let's even start it off
with a quick require statement right we
want to require
that the unique
token state
of this user
going to be greater than 0
right and if it's not we'll say
they don't have any tokens state right
so the value is going to be nothing
now if this is true
if they have some token staked
we'll go ahead and find it so we're
going to loop through those allowed
tokens up here
the allowed tokens and we're going to
find how much this user has for each one
of these allowed tokens
so we're going to say 4
uint
256
allowed tokens index
equals zero allowed tokens index is less
than allowed tokens dot length
allowed tokens index plus plus
and let's go ahead and we'll add the
total value and now we'll say the total
value is going to be equal to
the total value plus
however much
value this person has in these tokens in
this single token so get user total
value is the total value across all the
different tokens we need a way to get
the total value across one token so
we're going to create a new function
called get
user single token
value
and we'll pass it our user
and we'll also pass it the single token
that we're on right now so we'll pass it
allowed tokens
allowed token index
so we got to create a new function here
function get user single token value
this is going to take an address of a
user and an address of a token
it's going to be a public function
i'm just going to put this on a new line
to make it a little easier to see it's
going to be a view function
and it's going to return
a u in 256. we want to get the value of
how much this person staked of this
single token
so for example if they've staked
one each
and the price of one eath is two
thousand dollars we wanna make sure that
this returns two thousand
or if they have two hundred die stakes
and the price of two hundred die is two
hundred dollars we want to make sure
this returns 200 right so we're getting
that conversion rate we're getting
exactly how much value this person has
staked in our application now we'll do a
quick if we'll say if
token staked
of the user
is less than or equal to zero
then we'll just go ahead and return zero
right we don't want to do a require here
right as we did up here because we want
this to actually keep going right if
this is zero we don't want the
transaction to actually revert okay we
want this to keep going so how do we
actually get
the value of a single token well we're
going to need to get the staking balance
right but we also need the price of that
token so we're going to need to get the
price of the token
and then multiply that
by the staking balance
of the token
of the user so once again we need to
create another function we'll call this
one
get token value
so in another function
we're going to call get token value
you could pass an address of a token
we'll make this a public view function
that will return
a uin256
and this of course is where we need some
pricing information and this is where
we're going to actually work with the
chain link price feeds once again and
hopefully this part is going to be a
little bit more familiar for you
so what we're going to need is a price
feed
address that's the first thing that
we're going to need so we're going to
actually have to map each token to their
associated price feed addresses so we're
going to need some mapping that does
that right so we're going to need some
mapping
that's going to map
an address
to
an address
it's going to be a public one and this
is going to be token
price feed
mapping right it's going to map the
token to their associated price feeds
and with that that means we're going to
have to have a function
called set
price feed contract
where we actually set the price feed
associated with
a token
so this will take an address of a token
and an address
of a price fee
this will be a public and this will be
only owner
we don't want anybody to be able to set
what these price feeds should be we just
want the owner to be able to do this
so we'll do token price feed mapping
of the token
is going to equal
the price fee and that's it so now we
have a way to set the price feed
contracts we have a way to map the
tokens to their price feeds right and
again
go to docs.chain.link we can go to price
feeds ethereum price feeds we can find
these different price feeds here and
this is where we're going to set those
price feeds now back down in our get
token value
we can grab that price feed address now
by saying
address
price feed address is going to equal
that token price feed mapping
of
that token parameter and now that we
have this we can use it on an aggregator
v3 interface again we can always go back
to the docs here we can grab this bit
right here
of course we're going to change it
to 0.8
and for those who would rather i just
wrote it out
we're going to import
at chain link slash contracts slash src
slash interfaces
slash agreed gate or v3 interface
dot sol
and since we're doing this import
we're gonna go to our browning config
smart contract kit
chain link
brownie contracts
and we're going to see what's the latest
version of these
now i'm going to point something out
this package recently changed to mirror
the mpm package versions so it does look
like it went backwards in versions and
there's even a little little update here
but this is the the newest version even
though it's a 0.2.1 it's literally just
to match the mpm contract tags
so this is what we're going to use so
we're going to at 0.2.1
and then in our remappings we'll also do
at chain link
equals
this bit right here
now that we've imported that we can now
grab that aggregator v3 interface
or that price feed
and say
aggregator v3 interface of price feed
address
and grab that price feed contract then
once we have this price view contract we
can call
dot latest
round data
and again you can always check back to
the documentation to see what that
function actually looks like and this is
going to return it's going to return a
whole bunch of stuff
but we only care about the price so the
first thing it returns is round id
we don't care about that so we'll just
put a comma
we do care about the n256 price so we'll
put that in there but we don't care
about the rest of these
so we'll just do
comma comma comma
because we only care about the price
here
we also care about the decimals we need
to know how many decimals the price feed
contract has that way we can match
everything up to be using the same units
so we'll say u and 256
decimals
equals price fee dot
decimals
and what we can do now is we can return
both of these so this actually needs to
return a un256 and another uint 256.
put the decimals here
and we do return
we can return both of these so we'll do
a uint
256 price we'll wrap that price into a u
and 256 and then we also need to wrap
the decimals in the u and 256 since
decimals actually returns a u uint eight
so we'll return the price and the
decimals all right now we're cooking
now
we can go ahead and start scrolling back
up and adding all this stuff in so we
can say you and 256
price you went 256 decimals
equals
this get token value that we just
created right here and then we can just
have this return
staking balance
of the token
of the user times the price
and do some interesting math here
divided by those decimals
10
raised to
decimals
and i know there's a little bit of math
here right and so you might be going
wait wait what are we doing here wrap
that up like that just so that we're
absolutely certain we're doing correct
order of operations here
so we're taking the amount
of token that the user has staked right
let's say for example
10 die
and we're taking the price of that die
maybe we have
all of our contracts all of these tokens
get converted back to the usd price so
we have die
usd actually better yet let's say we
have 10 eth
right our price feed contract is going
to be eth usd
let's say the price
is is 100 100 dollars per usd
so this first bit is we're going to do
that 10 eth
times 100 so we're going to do 10
times 100 which is going to equal to
1 000. 1000 value the only thing is we
also have to divide
by the decimals so our staking balance
is going to be in 18 decimals so it's
going to be one two three four five six
seven eight one two three four five six
seven eight nine ten
but let's say our fusd only has eight so
one two three four five six seven eight
so we need to multiply these first
and then divide by the decimals that way
we can arrive at a price that actually
makes sense is going to be a function
that we're definitely definitely
definitely going to need to test to make
sure that we're doing everything right
so that we're doing all the math
correctly but okay now that we have this
user single token value we go ahead
and come back up to our user total value
and we can literally finish this
function by just calling return
total value
and then we can pull up to our issue
tokens now that we have the total value
that this
user has actually logged we can just
transfer the amount of tokens that they
have in total value so we can say dap
token
dot transfer
this recipient we can transfer them
the total value right we'll say however
much they have in total valued staked on
our platform we'll issue them as a
reward and that is our issue tokens
function we are making great progress
all right so we have a way to stake done
we have a way to issue
done
we have a way to get
value or just get value
done
we've added a way
[Music]
to add allowed tokens and all we have to
do now is add some way to unstake the
tokens
so let's go ahead and create this
function
i'm going to make it right underneath
the state token one
we'll do function
unstake tokens
we'll do we'll pass it the token address
we'll make this a public function so
anybody can call this the first thing
we're going to want to do
is fetch the staking balance how much of
this token does this user have so we'll
see you in 256
balance equals
staking balance
of the token
from message.sender
and we're going to require
the balance
is greater than zero
otherwise we'll say staking
balance
cannot be zero
and then we're going to do a transfer
so we'll do ierc ierc20
of the token
dot transfer
message.sender
balance
once we actually transfer the token
we'll do staking balance
of this token
of message.sender
we're going to update this balance
to now be zero right because we're going
to transfer the entire balance here and
then we're going to update how many of
those unique tokens that they have
now a quick note here later on we're
going to learn about reentrancy attacks
so at some point come back here and
figure out hey is this vulnerable to
re-entrance the attacks so we'll say
unique
token staked
of message.sender
it's going to equal
unique token state
message.sender
minus 1.
now the last thing that we could do is
we probably should actually update our
stakers array
to remove this person if they no longer
have anything staked this is a little
bit sloppy but we're just going to skip
doing that for the time being however if
you want to go back and add the
functionality to remove the stakers from
the stakers list as they unstag please
go for it it's not a big deal if we
don't actually do this because our issue
tokens function is actually going to
check to see how much they actually have
staked and if they don't have anything
staked then they're not going to get
sent any tokens
but all right that's basically all of
the functionality here
let's just try a quick sanity check with
a brownie compile
whoops i forgot to add v0.8 in here
let's try again that little bit
this needs to be token
and this needs to be user whoops and
then it looks like i did the same thing
down here this is actually staking
balance
let's try it again
and perfect everything is at least
compiling correctly just because it's
compiling correctly though doesn't
necessarily mean that we're doing
everything correctly
so this is fantastic typically now we'd
want to go ahead and start doing our
tests i'm actually going to go ahead and
build one of our scripts first the
reason i'm going to build one of the
scripts first is because i'm going to
use my deploy script pretty regularly in
my test i'm going to use it as part of
my testing this way i can also test some
of my scripts as well in addition to the
contracts so let's go ahead and make our
deploy script
so let's create a new file in here
we'll call it deploy.pi
we'll also create
an init.pi for those of you on older
versions of python and let's go ahead
and do this so we're going to have a
main function in here and in our main
function we're actually just going to
call deploy
token farm
and
dap token
and then we're going to have a function
def
deploy
token farm
and
token
right and i should be able to run
running run scripts deploy.pi
and great everything's compiling right
and we're running our scripts here so
first thing that we're going to want to
do as always is get our account and i am
going to copy a couple of those helpful
scripts from our past projects so i'm
actually going to pull up our nft demo
that we did so i'm actually going to go
to our chain link mix that we did i'm
going to grab our helpful scripts
remember we can always jump onto the
chain link mix here and we can just grab
some of the scripts from here so we
could go to scripts helpful scripts and
just copy paste this whole thing or just
grab it like i did right these are going
to be those exact same scripts that we
built previously so now we have our
helpful scripts in here right we're
going to have this contract to mock for
running our tests we have get account so
we can get our accounts easily we have
encode function data which we're not
going to have to work with since we're
not doing upgradable contracts but we
have it here anyways we have upgrade
which we're also not going to use but we
have it here anyways we have get
contract which returns mocks if they're
not already deployed or it just returns
whatever contract that we're looking for
and then of course we have our deploy
mox script here so now we can do from
scripts dot helpful scripts
import
get account
and perfect we can get our account like
that no problem now and now we're going
to want to start deploying some
contracts so we're going to deploy that
dap token first so we'll do from brownie
import dap token and we'll do
dap token
equals
gap token
dot deploy
and this takes no parameters so we can
just do from
count
then we're going to want to deploy our
token farm
so we could say tokenfarm equals
tokenfarm.deploy
and this takes one parameter which is
the dap token address right because we
need that address so we can give it out
as a reward so we're going to say
dab token dot address we'll do a comma
and then we'll say from
account
and we'll need to import this
from
brownie as well and while we're here we
might as well add some publish source
bits on here so we can say publish
source equals
config we'll grab this from the config
networks
network dot show active
verify
grab network from brownie
grab config from brownie
and in our
config here
let's do networks
lad development
we'll set the verify here
to be false
and then we're going to work with the
coven chain
so we'll say coven
verify will also be false actually kovan
sorry covenant will be true
and then we'll do a persistent ganache
or verify for this will be false
and i'm even just going to put this up
here so that all these
ganache chains are kind of with each
other so we'll verify in coven but we
won't on development or ganache
now once we've deployed this token farm
contract we need a couple things right
we're going to need to send this some
dap tokens right we're going to need to
send pretty much all the dap tokens so
that i can actually give those tokens
out as a reward so we're going to want
to do a transaction it's going to equal
to
dap token
dot transfer
we'll send it to the token farm
address and then we have to choose how
much we're going to send and we'll send
the total supply
but we'll keep a little bit for
ourselves so we can do some testing and
so just in case so we'll also do minus
kept
balance some static kept balance which
we can say
at the top
we'll say the kept balance is let's keep
like 100
so this will be equal to
web 3.2 way
100
ether
so we'll do
from web 3
import web 3. so in our transfer we'll
do
dab token dot total supply minus the
kept balance and then of course we're
gonna have to do a from
[Music]
account
so now we're sending
our token farm basically 99.9
of the total supply of this dap token so
that it has this token to actually give
out as a reward we'll do a tx
dot wait we'll wait for one block
confirmation there now what do we want
to do well if we look at our token farm
we know at our state tokens function we
can only stake tokens that are allowed
in each one of these tokens also is
going to need to have some price feed
associated with it right and our token
price feed mapping
so we're going to have to add those so
what we're going to want to do is we're
going to want to create a function
called add
allowed tokens and what this is going to
do it's going to add the tokens that we
want to allow and it's going to give
them a price feed contract associated
with them so let's create this function
we'll call it def
add allowed tokens and this is going to
take a couple things we're going to want
to take that token farm because we're
going to need to call the add aloud
tokens function on it we're going to
take a dictionary
of
allowed tokens and this is going to be
the names this is going to be a
dictionary of the different token
addresses and their associated price
feeds so we're just going to price
everything in usd so so we can figure
out the value of everything in usd and
then last of course we're going to need
an account
for now i'm just going to do pass here
let's look at the different inputs that
we're going to put into this so
obviously we're going to do token farm
but then we're going to need to make
this dictionary of allowed tokens so
we're going to need the address of the
different tokens that we want to have
now how do we get the addresses of the
different tokens that we're going to use
and what are the tokens that we're even
going to use here
for simplicity we're just going to start
with three tokens we're going to allow
our platform to allow three different
tokens to be state we'll use the dap
token
as one
we use weth token or wrapped eth because
that's pretty much a standard in most
smart contract platforms and then we're
also going to use an fau token which
stands for faucet token and we're going
to pretend that this fafsa token is dye
or dai the reason we're going to use
this faucet token is because there's
this erc20 faucet.com which allows us to
get this fake faucet token we can get
unlimited amounts of this faucet token
on different test nets we're going to
pretend that this faucet token is going
to be die right so fau token slash die
so how do we actually get these
addresses well dap token we know with
token
what we can do in our config so we can
actually add those addresses here
so for coven
the weath token address is going to be
this right here which again you can go
check this out
and you can find it on etherscan you can
write your own if you want we're just
going to use this already deployed one
on coven fau token which is gonna be
this token here which i know is gonna be
this address right here
and if you want you can come here
and grab your address
paste it into this erc20faucet.com
put an amount of 10 in here
connect to metamask oh and even tells us
the token address right here which we
can just copy paste we can do mint free
tokens confirm
great says success if we don't already
have it we can take this token address
go to our meta mask
assets
add token paste it in i've already got
it
we can see right now i have 5 fau
once this confirms i'll have an
additional 10 and now you can see 15
here this is going to be this fau token
that we're going to use we have wes here
and then we know
what the depth token address is going to
be
for when we deploy it here
now we could do again we could do the
config
you know networks
etc and just always get it from our
config
or we could use our get contract method
that we grab from our helpful scripts
which will deploy a mock weath token it
doesn't exist in one of these and that's
what we want because we're going to want
to test this locally so we're going to
want to deploy our own fake weath token
so we'll say the weath token
equals get contract
with token
and then the fau token
is going to be get contract
fau token and remember what we put in
here our string that we put in here
needs to match our string in our config
now in order for this get contract to
work for weth token and the fau token
we're actually going to have to modify
our helpful scripts here so if we copied
and pasted it directly from our chain
link mix this is basically what we're
going to have here we're importing all
of our mocs which we can go ahead and
copy paste these as well from the chain
link mix our test our mock contracts
here
we have some forking implementations we
have contracts to mock which tells us
based off of the key
what token or what contract we use to
mock we have get account which we use
all the time in order for us to do this
contract to mock correctly we're going
to have to mock west and fau and
actually we don't even need all these in
here we don't even need this whole
contract to mock in fact we can get rid
of
mock oracle we can get rid of vrf
coordinator and we can even get rid of
the link token for this we do need this
sdusd price feed later on
so i'm just going to leave it in here
for now we definitely do need though fau
token which is going to be mocked to
something and we need weth token which
was going to be mocked to something else
so what are these tokens going to be
mocked to well they're each an erc20
mock but we want to give them kind of
their own identity so what we're going
to do is we're actually going to make a
mock erc20 for both fau
and for web so we're going to come in
here we're going to do new file we'll
call it mock die
dot sol
and this is going to mock that fau token
so it could be mock die it could be mock
fau whatever we want it to be and we're
just going to make this a basic erc20 so
we'll do pragma
solidity
0.8.0
we'll import at open
zeppelin
contracts token
ear c20 your c20.sol obviously this is
going to look
very familiar this should spell pragma
not whatever i just spelled this is
going to look really similar to that dap
token so now we can call contract
mock die
is erc20 and we'll do constructor
public erc20
mock die
will be the name of this
and the symbol will be die and perfect
and that's all we need we'll copy this
whole thing and then we'll do the same
thing for
mockweath.soul we'll paste this whole
thing in here
and we'll just change the name call this
mock west
crc20
mock weft
and this will be
what token right so now that we have
those mocks in here we can change fau
token to
mock die
and west token to
mock weft we can import those from
brownie and in fact we can get rid of
the mock oracle here and the vrf
coordinator
instead we'll do mock die
and mock west
now of course since we have diusd price
feed and fusd price feed we're going to
make sure we have these in our mocks
here and then we're also gonna have to
deploy these in our deploy mox script
below
so if we scroll down to deploy mocks we
can see this is what it currently has
which is pulling directly
from the chain link mix so we just go
ahead
delete the vrf coordinator mark and the
mach oracle and instead
we'll deploy
those that mock weath and that mock die
so we'll do print
deploying mock die
die token equals
mock die dot deploy
from
account
and then we'll do print
f statement
floyd to
die token.address
and then we'll do
print
deploying
mock mock web
and then we'll do
[Music]
left token
equals
mock west dot deploy
we'll say from
account
and then we'll print
this deployed
be another printf
with token.address
now additionally
we have our fusd price feed left over
from the chain link mix we also need
this die usd price feed
so we can go ahead in here
we'll add
usd price feed
and we'll set this as a mach v3
aggregator we could do is we could
parameritize this up so that the mock v3
aggregator takes maybe some different
decimals a different initial value so
that these could be different
but for the sake of testing we're just
going to leave them being the same here
so great so we have the address of the
wet token we have the addresses of the
fau token and if those don't exist on
the network we're working on we're going
to deploy a mock so now that we have all
these addresses we can do a dictionary
of allowed tokens
is going to be equal
to this dictionary that we make so we're
just going to route each one of these
contracts like the depth token
to
its equivalent price feed for the dap
token we're just going to say that the
dap is going to be equal to die
we're going to say the fau token
is also equal to die
and our weath token
of course is going to be equal to eth
so we're going to want to get a usd
price feed another di usd price feed
and an f usd price feed so in our config
we can add i usd
price feed
and since we're going to be testing
since we're going to be doing our
integration test on coven here
we'll come to the chain link docs
we'll go to ethereum price feeds
we're on coven
and we'll scroll down to
dye usd
which is this address right here
pop that in and then we'll also want the
fusd price feed
which we'll also go grab that from here
on the coven network and we'll grab that
from right here
and we'll paste it in
so now to complete this deck we can do
this get contract again and we'll deploy
mock price feeds if they don't exist
so now we can just do
get contract
die usd price feed
fau token is also going to be usd price
feed
and then our weft token is going to be
fusd price feed and awesome now we have
our dictionary of allowed tokens that we
can pass to our ad allowed tokens this
will map
the tokens and their addresses with
their associated price feeds so we can
get them all to equal the same value in
our contracts so we can go ahead and
create this function called add allowed
tokens we'll pass it this token farm
we'll pass it the dictionary of allowed
tokens and then of course we'll pass it
the account
now in our add allowed tokens function
we're going to loop through all these
different tokens and call the add allow
tokens function on it so we're gonna do
four
each token in the dictionary of allowed
tokens we're gonna do tokenfarm.add
allowed tokens
and we'll do the token.address and we'll
do from
account
we'll say
add tx equals that
we'll do add tx dot weight
1
then we're going to call this set price
feed contract so we're actually going to
set the price feed associated with that
token
so we'll do
set tx
equals token farm
dot set price feed contract
and we'll do token.address
the dictionary of allowed tokens
of
that token that we're for looping
and then of course
from
account
and we'll do
set text.wait one
and then we'll just return
the token farm but we probably don't
have to return anything and great that
deploy script looks pretty good and in
fact we're going to end our deploy
script here with returning token farm
and
adapt token this way we can actually use
this deploy script in our tests so i'm
just going to do a quick little zoom out
and we can see
our wonderful deploy script right here
and awesome it looks like we have just
about everything here
let's give this an initial test
on a local ganache chain see if our
mocks all work see if everything at
least makes sense we can call our
functions awesome it looks like we can
call all of our functions
and we can deploy our mocks and the
mocking is working at least somewhat
correctly here this is great we'll zoom
out a little bit here we've got our
deploy scripts we've got our ad allowed
token scripts we've got all of our mock
contracts added under tests things are
looking good now what do we want to do
here
well of course we want to run some tests
we want to make sure our contract is
actually going to do
what we say it's going to do you guys
ready let's jump into it so in our tests
let's make a new folder called unit
we'll add a new file we'll call it test
token farm dot pi let's do some tests
now ideally we would also write some
tests for our dap token however we're
going to skip over those because we're
basically just doing open zeppelin's
implementation
but in a full-scale production here you
probably would want to write some tests
on your tokens as well so let's get into
this let's look at our token farm and
see what we need to test remember
ideally every piece of code in our smart
contract here should be tested in some
form or another so with that in mind
let's get started so one of the first
functions that we see is set price feed
contract so let's make a test for that
so we'll do def
test
set
price
feed contract
and we're literally gonna test just this
one function so how do we test that well
first let's make sure we're on a local
network right because we only want to be
doing this
on our local network since this is one
of our unit tests
so in our arrange stage
we're going to do if
network dot show active
is not in
local
blockchain
environments
then we're going to run pi test.skip
and say only
for
local testing of course we've got a
number of pieces here that we need to
import we're going to do from browning
import network
we're going to do from
scripts.helpfulscripts
import local blockchain environments and
then
we're going to import
pi test all right so now we're going to
get an account
to make these transactions we'll say
account equals get count and let's grab
that for my helpful scripts as well so
now we have an account we can use let's
even grab a non-owner account so we'll
say non-owner
equals get account
and we'll do index equals one this will
give us a different account rather than
this account and we'll use this to check
some only owner functions and then what
we're going to do is we're going to get
the token farm
and the dap token
based off of
our deploy script so we're going to use
this deploy token farm and dap token
we're going to import that by saying
from
scripts.deploy
import
deploy token farm and dap token and
we're just going to call this function
in our test right here so we're going to
say token farm dap token equals deploy
token farm and dap token awesome this is
how we're going to do this a lot this
arrange step for a lot of these tests
here because this is how we're going to
set them up we could even hypothetically
turn this into a conf test or into a
wrapper if we wanted to but we're just
going to leave it in here like this for
now now we can move on to our act phase
so we're going to want to do
token farm
dot
set price feed contract
because remember
this is what we're testing right now and
we're going to use
a token and a price feed address so we
use the dap token dot address we'll use
get contract to actually get an fusd
price feed address
which we can also grab
for my helpful scripts get contract an
important note here if you try to set a
contract as an address parameter like
this ronnie will know okay that you're
looking for an address instead of the
actual contract in any case then we'll
do from
account
save it and it re-shifts over here now
this should work perfectly so we're
going to assert this
we're going to move into our assert
stage right
if we check our price feed mapping
this should now be updated
so we can do
assert
token farm
dot token price feed
mapping
and remember
token price feed mapping is an address
to an address so we'll say dap token
dot address this should be equal to
get contract
of fusd
price feed
this should be updated with exactly what
get contract of fuc price feed returns
in fact we can even make this a little
bit better
copy this we'll say
price feed address
equals get contract and then we'll
pop this in here and we'll pop this here
that way now we're just using this
single variable for both
all right that's our first test let's
run it brownie
test this will run the whole test suite
and we're passing awesome now let's also
do a test
to make sure that
non-owners can't call this function we
want to make sure that somebody other
than the owner who deployed this right
because deploy token farm and dap token
is going to be run by get account we
want to make sure that
somebody else can't call this function
so we'll do with pi test dot raises
exceptions dot virtual machine error
excuse me for that
getting in the way and then we'll try to
call this exact same function here right
we can even just copy paste it
but instead we'll
call it from non-owner
right
and then we do also have to import
exceptions from browning so this should
also pass
it's expecting this contract call to
actually revert so let's try this
perfect it passes
right we can double check to make sure
that this pi test.raises is working
because what if we did a count here
right
this now should fail because this isn't
going to revert and that's exactly what
happens perfect so we can leave this as
non-owner and our first test is looking
great let's even zoom out just a hairier
we can sleep easy that this function is
going to work as we intended isn't that
a wonderful feeling yes it is great
let's move on so let's look at our token
farm what's the next function aha
issue tokens all right great let's write
some tests for issue tokens so what are
we going to do
def
test
issue
tokens so how are we actually going to
do this well in order to test issuing
tokens
we actually need to
stake some tokens first
so for now i'm actually just going to do
pass here and before we test issuing the
staking tokens we need to write a test
for staking those tokens right because
in order to issue tokens you need to
have some tokens state so let's write a
test
stake tokens first and then we'll write
this test issue tokens so we'll do def
test
stake
tokens
now let's set this up
so we're going to copy this bit here
because we are going to be working on a
local network with this we'll do account
equals get account and then
we'll go ahead
and deploy the token farm and the dap
token so
this initial bit is going to be exactly
the same making sure we're on a local
network getting the account deploying
the token farm and the dap token
so now let's move into the act phase
let's go ahead and act let's go ahead
and actually send some tokens to our
token farm so first we obviously need to
call approve on the dap token contract
so we'll do dap token
dot approve
to the token farm dot address
and again you can see and again we can
go to the open zeppelin docs to figure
out what the parameters of this are but
it's going to be an address and it's
going to be some amount and then
obviously from
account
now i put a couple question marks here
because we're going to constantly be
using an amount right we're going to be
using an amount staked for a lot of our
tests here
so what we're going to do is we're
actually going to turn that into a
fixture
we're going to call it
amount
state and we're going to define this in
our conf test folder so we're going to
make our conf test file so in here we're
going to do new file
conf test dot pi
and whoops it's in the wrong directory
so we're going to go cd tests
units
i'm gonna do move
confidence.pi
down one directory and it should be in
here now if that didn't work you should
be able to drag and drop it
uh into test you just wanna pull it out
of unit is what we're doing here right
just want to get it so that's just in
this test directory here in the case in
our conf test.pi we're going to create
our first fixture
so we're going to do at pi test.fixture
we'll do def amount staked
and then we're just going to return
web3
dot 2 way
one
ether now of course we need to import pi
test here
then we're going to need to import we're
going to do from web3
import web3 and now
it saves
perfectly so now we can use this amount
staked fixture as basically a static
variable right we could have done at the
top we could do something like amount
staked equals you know that exact same
thing but
we're going to get into the habit of
working with these fixtures so we have
our def test stake tokens and we're
going to pass it this amount staked
fixture pi test and brownie will
grab all this stuff from the conf test
folder and put it into here
so now we can just use amount staked as
a parameter in our test here so once we
approve we can then do token farm
we now call
our stake tokens
function right here
and it takes an amount
and then a token address
so of course we're going to do amount
staked
as the amount and then we'll do depth
token
address
as the address and of course from
account
and perfect this is going to be our
basic action of testing the staking
functionality so we can go ahead and
down here and move into our assert phase
and we can just assert a number of
things
right
and do a little
bracket here
we're gonna do a couple of things here
we're gonna assert the token farm
that's staking balance
of dap token
that address
of account dot address
equals amount
state
so let's talk about this really quickly
what is this actually doing so if we go
to our token farm we know that we have
this mapping called staking balance and
this is a mapping of a mapping
right so we need to actually pass
two variables the first address and then
the second address to get this amount
this is how you do that syntactically
with brownie you just pass it as
additional parameters in here so we pass
the dap token address
which is going to be the token address
here
and then the account address
which is going to be the address here
and perfect
so we can even run this by doing brownie
test
dash k
test stake tokens
and great looks like that passed
perfectly
but we have a couple of other assertions
to make right because if we look at our
stake tokens function it does a lot of
things so let's check all of these and
make sure that they all are working
correctly so we'll also assert
that the
dot tokenfarm.unique
token staked
of account that address
is going to be equal to one right this
is going to be the first token so
it should have a unique token state we
should also assert that the token farm
dot stakers
at the zeroth index is going to be
this account that we're using we update
our unique token staked
we update our staking balance
and then we add
stakers.push right so we're going to be
the first
address in this array now and then i'm
going to do one other thing here too i'm
going to do return
token farm
and dap token
the reason i'm doing this is because now
we can actually use this
test in some of our other tests now
we're getting a little bit integration
here we're kind of mixing and matching
some stuff we could even probably put
this whole thing in a function in our
regular scripts directory but for
simplicity's sake this is how we're
going to architect it but great let's
test the rest of those we'll just hit up
ground to test k test stake tokens we'll
hit enter and perfect
this is passing correctly as well
awesome let's keep going now we're
moving into this test issue tokens phase
here and we're going to use our test
stake tokens test here
so the way that we're going to use this
is we're going to grab this amount
staked parameter
place it in here
and we're going to set this up exactly
the same way we're going to set this up
almost exactly the same way so we can
even just copy these few lines here
paste it
we're going to do an arrange
we're going to check to make sure we're
on a local network we're going to get
our account but instead
of doing deploy token farm and dap token
we're going to do
token farm
comma dap token
equals test stake tokens and we're going
to pass it that amount state so this is
why we're returning the token farm in
the dap token in our test stake tokens
that way we can use that function now
in our test issue tokens and perfect now
we can test issuing these tokens so to
test issuing tokens to issue this reward
we want to first take some inventory of
the current starting balances of our
address we'll say starting balance
equals
depth token dot balance of
account dot address and great this is
how we're going to start off in our
range phase now let's move to acting
open our act phase and we'll just do
tokenfarm.issue tokens
we'll save from
account
and this is really the only thing that
we're testing here so now we can move
into the arrange
stage
and we'll do assert
i'm going to do a little
parentheses here because this is going
to be a long thing and we're going to
assert that the dap token
dot balance of
the account dot address
should equal
the starting balance
plus
some new amount
what's that new amount going to be well
if we look at our issue tokens function
if we're staking in our conf test if
we're staking one
ether right
or one
die right because we're staking the dap
token we're just taking one our marks
are going to be this
fusd price feed right our mock v3
aggregator when we deploy it the initial
value is going to be this 2000 right
here and we're saying
in our mock in our sample here we're
saying
we are staking
one
depth token
which is equal
in price
to one each
so we should get 2 000 depth tokens in
reward since we're saying
since the price
of eth is
2000 usd
so there's a little bit of math here
but the initial value is going to be
2000 right you can almost think of it
like this
with 18 decimals and our application
pays us reward based off of the total
usd value that we have locked so we
actually can know that this is going to
be that 2000 price so what i'm even
going to do is i and if this isn't
already in the chain link mix shame on
me i should add this in here
because we're going to add a new
variable called initial
price feed value
it's going to be equal to 2 000. one two
three four five six seven eight nine ten
one two three four five six seven eight
that super big number and we're gonna
take that and we're gonna set that here
to our initial value is going to be now
this initial price food value
and what we can do in our test
is we can then import that
from our helpful scripts
and we can just assume that our starting
balance is going to be now we are
starting balance plus that initial price
feed balance and if we've done our math
correctly and if we've done our issue
tokens and if we've done all of our get
value correctly this should work we
should have done our testing already
on the things like get
user total value right because get user
total value is a subset of issue tokens
but we're jumping the gun a little bit
here and we're going to test this later
on anyways so
with that being said let's run this test
brownie
test dash k
test issue tokens and lovely so our math
is correct
awesome we are doing wonderfully with
her tests here we've even gotten some of
the harder ones out of the way early
which isn't too bad either now as far as
this video goes we're actually going to
stop writing the test because we're
literally just going to keep going down
that solidity file and grabbing
functions and adding tests to them we've
got all the tests located in the github
repository associated with this lesson
there is both a unit test file and an
integration test file in the github
repository if you want to just go ahead
and check that feel free to do so we're
going to move on to the next section to
keep things moving forward but i highly
highly recommend you trying to write all
these tests yourself so good luck we're
gonna have all right now we're going to
umv
private
and our website
make sure your integration projects work
well make sure that you get started if
you run your deployment on copy paste
network directly
we're going to be testing everything
works we'll save dots of course you're
going to want to get out.env file you're
going to want to add that to your
browning config address privacy and add
your web3 inferior project id and make
sure you have plenty of test dent coven
so that you can actually run these
deploy scripts we can always find the
latest faucets from the link token
contracts page under our coven or rink b
networks here we're also going to need
our wallets section we'll do from key
and this is where we'll put the dollar
sign
private
key
now
now that we've got the contract now that
we've done all the contract work we're
going to learn something totally new
that we haven't covered yet we're going
to learn to do some front end
development now like i said this isn't a
front end course and the focus isn't
going to be on front end and i want to
point out right away that this is
considered a bonus section there are a
ton of pieces in this section that we're
not going to have the time to go over
thoroughly because we're not going to be
going into what's going on on the front
end side the editing is a little bit
choppier and i highly recommend having
the documentation having the github
associated with this front end with you
while you're going through this free
code camp has an awesome video on doing
front-end work and if you want to learn
more about react and typescript and some
of the technology that we're going to go
over definitely check out those videos
after this we're going to make this
though so that you should be able to
follow along with everything that we're
doing if you're not interested in front
end feel free to go ahead and skip this
part
however understanding how these front
end applications work is really helpful
and it'll give you a
massive massive incredible skill to
actually build front ends for your smart
contracts having a really solid user
interface is really important in the
web3 in the blockchain world if people
can't use your contracts then what good
is your application so with that being
said let's jump on and let's build our
front end
and i know we said we didn't like
javascript we're gonna be working with
typescript here which is a improved
version of javascript and catches a ton
of the different bugs and allows us to
be much more explicit with how we're
working with our front end we're also
going to be working with react we're
going to be working with create react
app this is a front-end framework that
allows us to quickly spin up a front end
to build for our applications here we're
also going to be working with this tool
called used app it's a framework for
rapid dap development
and works great with react here so let's
get started building this front end the
first thing that we're going to want to
do to build a front end for our full
stack application create react app
boilerplate so you should have mpx
installed if you run mpx-version
it should show up this should be
installed from when we installed npm if
you don't have mpx installed you can run
mpm install
g npx additionally we're going to want
to install
yarn here to install yarn again you just
run mpm install dash dash global or dash
g yarn you'll know you have yarn
installed correctly if you can run yarn
dash dash version you see a version of
yarn and i have a link to install both
npx and yarn in our github repo great
once you have those we can actually
create a folder with all of our
boilerplate code in it we're going to
run mpx
create
react app we're going to call it front
end and this is going to create a new
folder called frontend
and we're going to do dash dash template
type script
because we're going to want to work like
i said with typescript instead of
javascript for those of you who've never
worked with typescript before and who
have worked with javascript don't worry
the syntax is nearly identical for those
of you who have never worked with either
don't worry we're going to walk through
everything that we do and then we'll hit
enter here what's going to happen is
you'll see we're going to create this
new react app in this new front end
folder in our project here
awesome now that we've downloaded our
create react app we have this new folder
called frontend and it's got a whole
bunch of stuff in it now typically what
different applications will actually do
is they'll have one repository for all
their python and for all their contracts
but they'll additionally have a
different folder
or different repository for their
front-end application and their
front-end work this is really good
practice we're just going to bundle
everything up into the same repo here
just to get started and just to make it
easier for us getting started here
however what you will see across
different projects is they'll have a
totally separate repo for their front
end so let's take some inventory on
what's actually going on inside this
folder so the first folder you'll see is
node modules these are basically the pip
installs these are the different
packages pulled in from javascript and
typescript we can pretty much ignore
this folder for the majority of what
we're working with here next we have our
public folder we're also not really
going to go in here but it's got some
nice little images it's got our basic
index.html which has the html that we're
going to be running with it has a couple
logo images and it has a manifest the
manifest is something that we want to
change this tells our browsers a little
bit about what our app is and what our
app actually does so this is something
that we we would change but everything
in here is pretty self-explanatory the
short name of our application the long
name of our application some icons start
url this is something that if you want
to fiddle with it later absolutely
please go for it and then robots.txt
we're not going to talk about this at
all this helps web searchers and
indexers learn a little bit more about
your site we can ignore this one as well
so for the most part we're not really
going to do anything in the public
folder or the node modules folder our
source folder however we are going to be
spending a lot of time in it has our
app.css which includes a whole bunch of
formatting for html we have app.test.tsx
this is going to be testing our front
end
yes you can even test your front end
we're going to totally skip over testing
the front end which yes i know we've
spent a lot of time testing our
contracts if you want to learn more
about testing your front ends there's
some fantastic links in the github and
in the description to go over this
app.tsx which we are going to be
spending some time in and it's one of
our the main places for us to write some
code index.css
again a formatting and styling file
anything that ends in css
is some type of formatting and styling
all these tsx are going to be type
scripts index.tsx we're going to pretty
much ignore we are going to change the
logo and we can ignore all these last
bits here a package.json this file tells
our project what dependencies it needs
and node.js packages it actually needs
to get started we have a readme which of
course is a readme we have a typescript
config which gives us some options on
how to work with typescript we're going
to ignore this and then we have our
yarn.lock which is an auto-generated
file we're not going to touch it at all
because yarn is going to automatically
create this if you're not if you're
unfamiliar with yarn.lock and unfamiliar
with a lot of this stuff don't worry too
much about it this isn't going to be a
file you're really going to need to pay
attention to but okay
now that we've created the basic create
react app we can actually go ahead and
right now we can see what a front end
will look like so we'll cd to the front
end
we'll run yarn just to make sure we have
everything installed what yarn does is
it actually installs all of our
dependencies anything in this
package.json
yarn is going to go out and download
these dependencies and store them into
node modules
and then yarn.lock is going to tell us
exactly what it downloaded once running
yarn now it just checks to see it says
ah it looks like you already have
everything installed because when we run
create react app it already goes ahead
and downloads everything but now we can
just run yarn start
if you want to know where this is coming
from if you go in your package.json
and you look under scripts
these are the four different scripts
that we actually run
running yard start runs this mpx react
scripts start which will actually start
our front end so we'll do yarn start
you'll see react script start you'll see
it says starting the development server
and after a little bit of time
we'll get something that looks like this
edit source
slash app.tsx and save and reload and
this is a super simple front end
obviously this isn't at all what we're
looking for but we've now started a
front end which is fantastic it'll say
compiled successfully it'll say you can
now view frontend in the browser
it'll tell you exactly where it's
located on our local host on the network
and it'll give you any outputs from the
front end down below
so we're just going to stop the front
end for now by hitting command c or
control c and closing it down
of course if we reload now on the front
end it's going to be blank but great so
we have a really basic setup for working
with a front end awesome if we look at
an application like app.avi.com you'll
see they have like this really fun
connect button that pops up
and they've got some nice user interface
tools for actually working with the
blockchain we don't want to have to
reinvent the wheel and build all these
custom tools for doing this so we're
going to use this application called
used app or this framework called used
app which has a whole lot of these
already built in to get started
installing all we have to do is run this
command right here yarn add use dap
slash core so here in our front end
we'll do yarn
add at use dap slash core and this will
go ahead and install all the used app
pieces into our front end so we can
actually work with used app and not
reinvent the wheel with working with
wallets and working with ethereum and
other smart contract applications
awesome now we have that installed we
can actually go ahead and start building
our front end now what we're going to do
is we're going to go to
app.tsx folder and we're going to start
in here we're going to start adjusting
some bits in here so what we can do is
we can do the yarn start and we'll get
our a little react front end here now
what we could do is we go ahead and do
something like change anything in here
right see how this line says edit source
that app source slash app and saved
reload we could do we change this whole
line
being something just like
hello
we'll save it
it'll recompile
we can go back and now it just says
hello right so this is how we can
actually upload and update our front end
we have these these wonderful return
pieces here these return sections here
which will return the html to actually
render the front end and this is also
our starting point for allowing our
application to be web 3 compatible
so if we go to this use dap
documentation right we go to our getting
started section we have a little example
here that shows kind of what what
something should look like right but
it's not exactly clear where we put all
this code
so they do have this wonderful
step-by-step bit and this is probably
the most helpful bit here it says the
first thing you need to do is set up dap
provider with optional config and wrap
your whole app in it so we're going to
use these depth provider tags right this
is the open tag and this is the closing
tag we just wrap it around our app so we
can see here this this whole thing right
now
is our app so we could take this whole
thing
delete it right and if we save right now
we can go and see
our friend is going to have nothing it's
going to be blank this function app here
that's getting exported export default
app
and this is getting rendered in this
index.tsx we have this cool little
app.html tag thing right but any case we
want to wrap this whole thing with this
tag here right
so we can even just copy this paste it
in i can do dap provider and then my vs
code even auto adds a second dap
provider here we can delete this div
class name equals app
i'll just put put a little divider in
here and just say hi and at the top
we'll just import this dap provider
thing like what is this weird tag we're
going to import it so we'll do import
depth provider
from
and use dap
core
now if we hit save we'll get this weird
error saying hey property config is
missing in our dap provider and that's
because
this dat provider needs a config
associated with it so we need to add
this config bit into this dat provider
so we're going to do
config
equals at this first bracket says we're
going to type in typescript and the
second bracket is saying we're an object
here so in this config we're going to
tell our application
a couple of different things so we're
going to tell it what supported chains
there are what are the networks that our
application can actually work with the
default value for supported change in
used app is going to be mainnet
reli
coven wrinkby robsten and xdi since
we're going to be testing only on coven
and ring b we could just do chain id dot
coven
and chain id dot chain id
is another term that we can pull right
from our used app slash core right and
now if we wanted some other chain id we
could just go ahead and put it in here
right like if we wanted to work with our
ganache we could just do one three three
seven if we wanted some other random
chain we could just put the other number
in there right but chain id coven is
going to be 42 and chain id that ring b
is going to be what is it three yeah
three or what or whatever it is and this
is all we need to get started working
with in a web 3 a blockchain compatible
application so let's go back let's save
and we'll refresh and now it just says
hi
how's it going so we're going to spend a
lot of time in this source folder and
since we're going to be here a lot let's
let's do some cleanup just to cut down
on the amount of fat that we have with
that create react app
so app.css we're going to toss this
app.test yes tests are great but we're
going to toss it we're going to leave
index.css we do need index.tsx
we don't need this logo bit anymore
because we're going to use our own logo
we do need this
we also need this
and since we're not running tests
anymore we don't need this but i'm going
to leave it in here just in case you
guys want to later on go back and add
some tests great so now we're looking a
little bit lighter and in our app let's
just remove
amp.css let's remove logo.svb
logo.svg goodbye
now okay so we're going to create what's
called a component we're going to create
a header component now in react
components are basically where you you
put modular parts of your front end and
we're going to create one of these
components is going to be our header
component to do this we're going to
create a new folder called components
and in here
we're going to create a new file called
header.ts
and this is where we're going to put our
header stuff and we're looking to to
make a little button up here right we're
looking to make a little button in this
header so what we're going to do is
we're going to import some stuff so
we're going to import use ethers
at usdap
core again if we look at the
documentation real quick this use ethers
thing has got some cool stuff it's got
this activate browser wallet thing got
this account thing
it's got some it's got some cool stuff
so what do those actually do we're going
to start by exporting a constant
variable
called header this is going to be a
function and this is some really this is
some really fancy typescript syntax what
this is meaning is that we're saying
header is a function
and here's what the function is going to
do we're going to use this use easter's
thing to get a couple variables so we're
going to say constant variable
account
activate
browser wallet
deactivate
equals use ethers
in order for us to actually use these
though we need to figure out first if
the user is connected
so we're going to create another
constant variable we'll call it is
connected
and this is going to equal
an account it's going to equal an
account it's going to equal account does
not equal
on d find
so we're saying
if the account
is undefined we're not connected if it's
not undefined then great we're connected
so we're literally just looking to see
if there's an account here and whether
or not we're connected we'll decide if
we show a connect button or not so to do
that we're going to return
a div this is where we're going to
return
some html stuff and we've got to check
to see if we're connected so we'll do is
connected i'm going to use this question
mark which is known as a tertiary
operator
which means
if this is true we're gonna do something
and if it's false we're gonna do
something else so we're saying okay if
we are connected right what do we do if
we're connected here well
we're gonna create a button
we'll have the color
equal
primary
create this button here
and then my vs code auto makes these
closing tags we'd even leave this button
blank if we want or we're actually going
to put some fancy stuff in here and then
we'll put a little function in it we'll
say on click
equals
deactivate this is this deactivate
function pulled in from our use ethers
thing i should spell it right though and
we're going to call this button
oops there's a little
parenthesis next to this so this is what
this is connect thing does so we're
saying if if we are connected
right do this
now we're going to do a little
colon here
and this is going to represent what
we're going to do if we're not connected
okay if we're not connected what we're
going to show is a different button
color can still be
primary
and we're going to do on click
we're going to do
a function
activate browser wallet
then we close up the button tag with
another backslash button
and we'll call this one though
so if we are connected we're going to
show a disconnect button and then if
we're not connected we're going to show
a connect button and that's it right
just make sure all of your divs all your
tags are matched up and we can go ahead
and save this and if we look at our ui
you'll see nothing's changed right okay
well why isn't anything changed well
this component that we just made it's
living inside of this components folder
and we've exported this this header
variable this header function right
however it's actually not in our app
here right so if we look at our
index.tsx this is what's actually
getting rendered so we're just rendering
this app variable which is pulled in
from you know dot slash app right this
app.tsx so index.tsx is really our true
ground zero this is where everything
really comes from this is kind of our
entry point right this is our main
function you kind of think of it that
way that pulls from this app file that
we have here you can see in here we
don't have any reference to this header
right we have our dat provider we have
our div tag saying hi but we don't have
the header in here so what we need to do
is we need to import this component we
just made into our app.tsx so we're
going to do is we're going to import
header
from
dot slash
components
slash
header
and now we can take this header bit we
can place it
inside our header tags here we can just
do header
and we'll close the tag
by adding it right here we'll save
and we'll head back and now we can see a
little connect button here which is
great obviously it doesn't look great
but we have the functionality here which
is what we want if we hit the connect
button our meta mask will actually pop
up and say hey would you like to connect
which account would you like to connect
i'm going to go ahead
select my first one
next connect it's connecting
and now i'm actually going to be
connected let's go to
one of the supported networks like coven
and now we can see here we have this on
click equals disconnect if i click this
now oops i need to actually sorry i need
to put this
inside the tag here so we just moved on
click to be inside of this little button
here now we can see it actually says
disconnect and if i click it i get
disconnected and if i connect i get
automatically connected right so if we
look at our metamask we can see we're
connected right here right that little
little green thing we can also manually
disconnect by going right into our
metamasks click this connected thing
here
click the account and hit disconnect the
account and you'll see our front end
does indeed update awesome this is how
we can take our meta masks and actually
inject it into our front ends so we can
actually use the front ends great job
this is absolutely massive where we are
so far now you might be saying to
yourself hey patrick this is cool uh but
it doesn't look very good that's kind of
a gross button in the top right corner
can we can we style this up can we make
this look a lot nicer and the answer is
absolutely yes so there's a lot of
different styling packages out there you
can 100 write your own custom ones we're
going to be using one called material ui
it's a popular react framework for
creating components and just doing a lot
of styling and doing a lot of really
nice work so we're going to be adding
this to our project as well so to add it
we're just going to use this this line
and i'm just going to go ahead and do it
myself and come in here we're going to
cancel this with control c
we do yarn
add at material hyphen ui
core and this will give us access to
some really nice libraries
for styling all these buttons installing
a lot of the things that we're going to
be working with back in our header we
can add this styling here so we're gonna
do import
button
make styles
from
app material
hyphen ui
core
and we're gonna use their button and
their make styles if we look in the
documentation here you can find there
but this is double narration kind of
like what their default buttons look
like and this looks pretty good looks a
lot better than what we currently have
we're also going to be taking advantage
of their make styles bit here so make
styles is a way to actually do styles
for based off of different themes that
you can actually use with materials ui
we're not going to be working with css
files because we're going to be working
with this make styles instead if you
prefer css you can absolutely easily
translate these to css files so we are
going to add some used styles first of
all using make styles so in here we're
going to do
const
use styles
equals make styles and this is where we
put a theme in here we're just going to
set it to be a default theme um there's
some documentation if you want to go
ahead and add your old themes though so
this make styles function it's going to
have a container and in this container
we're going to add some
padding of theme.spacing
for we're going to add display
flex
we're going to add justify content
flex end
and then we're going to add gap
theme.spacing 1.
so this is really just some typical css
stuff now we're going to take this use
styles constant that we just made
and down here we're going to do const
classes
equals
use styles so now we have this classes
object that we can start working with
we're going to take this classes object
in our little is connected thing we're
going to do div
class name
equals a little javascript in here
classes.container
we're going to wrap this whole thing in
this div right and this is going to
style
this whole button div here so now if we
go ahead and do yarn start again because
we shut it off
if we come back here we're going to see
it's going to look a little bit
different now it's been moved over here
we have this like fun little disconnect
connect button
where there's some padding and it looks
a little bit nicer and we're going to
change all of our buttons to being kind
of this built-in button
from the materials ui
so we're going to swap out all those
buttons with this with our new button
here if we go back we can see it's
it looks even nicer now now that we've
swapped it out with that with that new
type of button right it's got a nice
little clicky feel to it and then we can
also do another line called variant
equals contained
for each of our buttons
so right next to the color primary we'll
do
variant contained and then now we go
back and we have
a really nice button now
so awesome now we have like a really
nice button let's create a component
that will contain the meat of our
application now though from materials ui
we're going to use what's called
containers right and these are nice
little containers that are going to
allow us to style and make these
different sections well we can use we
can import
this container bit from this materials
ui
by doing import
container
from at material
hyphen ui
core
in our app.tsx
and what we'll do to our header we'll
make a little container here
container
give it a closing tag container
and then maybe in here we'll put this
little div high right so we'll remove
that div we'll paste it in here and now
we can see that it's been formatted a
little bit right it's been pushed over
from the side it still says hi we're
going to want to do one more thing we're
going to give it a max width of being md
oops
max width equals md
and this max width now if we look in the
docs again on materials ui these are the
different sizes we have large medium
small extra large extra small and then
false right these are the different
options we can have for max with we're
just going to do medium so if we save
this now go to wrap we can see it's been
pushed over a little bit more it's time
to add our main pieces right we're going
to need that top piece for staking and
the bottom piece for unstaking so we're
actually going to create a new component
called main and this is going to be our
main component so we're going to create
a new file in components called
main.tsx so let's start by just showing
some information about our wallet right
showing what we have in our wallet
associated with what we have in their
smart contracts so we'll say export
a constant variable called main and this
will be a function here's that syntax
for
functions in typescript and javascript
in order for us to show what amounts
that we have in our current wallet we're
going to need to know what chain that
we're even on because the network that
we're on is going to determine where the
addresses are right because it's going
to be different if you're on coven or
mainnet etc now this is where it gets a
little bit interesting because obviously
with brownie we know where these
addresses are right and brownie keeps
track of this for us right it does it in
our builds folder in our deployments
folder if we look there now if you
actually deployed something to coven
you'll see this 42 you'll see some stuff
in here you'll see this map.json which
has the most recent deployments
of our tokens our tokens and our token
farm if you actually deployed it to
coven if you haven't deployed it to
coven i highly recommend you doing that
now as well this way we can test our
front ends against a real test net so in
order to get these addresses we're going
to have to ask brownie hey brownie what
are these addresses where are these
coming from so we're going to need to
grab some information from this brownie
config we're basically going to need to
get all the information all the
information that's in this brownie
config right because this has
has these addresses already and this is
what we want however it's really hard
for node.js to work outside of this
source folder so what we're going to
want to do is we're going to want to
send that brownie config to our front
end the way we're going to do that is
we're going to actually modify
by adding a new function
called
def
update
front end now the only reason that this
works is because we have both our
contracts and our frontend in the same
repository in the real world once you
deploy your contracts those addresses
are pretty much set so you can just copy
paste them over to your front end
repository but for us we don't have set
contracts yet so we need a way to update
our front end so what we're going to do
is we're going to send that brownie
config
over to the front end right that way our
main
can know where those addresses are
we're also going to need to send
so we need to send the brownie config
to our
source
folder we're also going to send
the build folder
why because this will have access to the
dap token address or any other mock
addresses that we're using we're going
to open up our brownie config and we're
going to paste and we're going to dump
the config into that source folder now
typescript doesn't work with the ammo so
well it works with json really well so
we're actually going to convert it from
yaml to json and dump it to the front
end so we're going to open up our
brownie config we're going to say with
open
brownie
config
yaml
we're going to open it in
read format
we're going to say as
brownie config
we're going to say config
dictionary
equals
yaml dot load
brownie config
loader equals yaml dot
full loader
so we're gonna have to import this yaml
from the top we're gonna do
import yaml
and what this yaml is gonna do
is it's going to allow us to
load our yaml into a dictionary that's
really it so you probably don't have it
right now you're going to want to run
pip install
pi yaml
to actually get it now we'll be able to
have that now that we've got this in a
dictionary we're going to want to send
this to the front right we're going to
want to write this dictionary as a json
object to our front end so we're going
to say with
open we're going to open that front end
source folder
and that's just where we're going to
dump this file we're going to call it
brownie
config
dot json
we're going to open this new file
in write mode we'll say it's as
brownie
config json
what we're going to do is just do what's
called a json dump we're just going to
take this dictionary and dump it as json
into this file so we're going to say
json.dump
config dick
brownie
config
json
of course we're gonna have to import
json and then at the end we'll even
print
front and updated so now we have this
update front end script what we can do
when we run our deploy token in-depth
token we can just add this update front
end bit now we don't want to always
update the front end right we only want
to do when we're working with the front
end so in our deploy token farm in depth
token we're going to set update front
end
equals false so by default this is false
this way when we run our tests
the front end won't get updated right
and down here we'll just say
if update front end
and we'll update the front end otherwise
we won't
and in our main function here we'll just
say update
frontend equals true now if we deploy
this to coven or rink b we'll
automatically update and send this
browning config and then let's actually
change this to front and update instead
of update front end so that we don't
have the same method name as our boolean
here so we'll do front
and
update instead so now
when that we deploy
we'll actually go ahead and update our
front end here but we're not always
going to redeploy so let's also
create an up
date front end dot pi script
and this we'll just call that function
that we just made so we'll do def main
update
front end and then we'll do from
scripts
dot deploy
import update
front end semicolon there great
let's open up a new shell
by hitting a little plus button here now
we have two shells and we can just do
brownie
run scripts
update front end doesn't matter the
network
and what this is just going to do
it's just going to run that copy script
right it's going to run our
our update front-end script which we
made right here so if we did this right
we should now have a brownie config.json
in our end
source directory so if we go in here we
go into our source directory we can
indeed see it's right in here do we need
anything else well so that's going to
give us those addresses right it's going
to give us it's going to give us some of
the addresses but it's not going to give
us everything what about dap token right
the app token isn't going to be
something in our brownie config last
token and fau token sure they'll be in
our config but dap token is going to be
something that only is going to be
deployed by us so we need to send that
to the front end too we need to send
basically our whole build folder so
we're going to need to update this
update frontend script to also send
send the build folder i know that we're
actually going to be copying a number of
different folders so i'm just going to
go ahead and make a new function called
copy folders
to front
end
and in here so we're going to make this
copy folders to front end function here
we're going to do a couple of clever
python things this is going to take a
source and a destination so we want a
source folder and then a destination
folder so we're going to copy this build
folder and move it to you know some
folder in the front end first we're
going to check that that destination
exists and if it exists we're gonna kill
it we're gonna we're just gonna remove
it so we're gonna say if os.path dot
exists destination we're gonna do this
shuttle dot rm tree
dest
and this is gonna kill everything so we
need to import both of those we're going
to import os
we're going to import
shuttle or shutil i actually have no
idea how to pronounce that but we're
going to remove that whole bit and we're
just going to copy everything over from
our build folder so we're going to do
shuttle dot copy tree src
dest so we're going to say hey if that
build folder exists in the front end
just delete it and we're just going to
copy everything over from the build
folder and we're going to do this copy
folders to frontend a few times
the first thing of course like i said is
going to be with this build folder so
we're going to do this copy folders to
frontend the source
is going to be dot slash build so we're
going to take this whole build thing and
we're going to move it to
dot slash
front end
src and we're gonna create a new folder
in here called chain
info right and this is just gonna have
all of the build information
and all right
cool so now we can run that
brownie run scripts update frontend
we'll go ahead and run that
and great front end is now updated so if
we look at our front end we're looking
source
we now have this chain info folder which
is literally just the build folder which
is awesome now we can actually start
working with these pieces in our front
end so let's figure out how to get the
depth token address
well to get this dap token address we're
going to need
that map that we just got from chain
info in our deployments but we're also
going to need to know what chain that
we're currently on like what we saw
before we have this chain id
from used app core which will tell us
what chain id of the current network
that we're on
so we can go ahead and import that in
here as well so we're going to do is
we're going to import
use ethers again
from
at use dap
core what we're going to do here
is use ethers
allows us to get the chain id that we're
working on so we can say cons
chain id
equals
use ethers now that we have the chain id
we're going to have to map it to the
name of the network right because our
browning config has this network section
but it's mapped by the name of the
network not by the id
so what we're actually going to do
is we're going to create a helper config
in our src
so we're just going to create a new file
helper config
dot json and it's literally
just going to be a json object that maps
numbers to their associated chain names
so 42 for example is going to be kovan
four is going to be rank b one three
three seven gonna be dev
or it could also be ganache right one is
gonna be mainnet etc now that we have
this helper config we can do import
helper config
from
dot dot slash
helpworkconfig.json
and before we even get the dab token
address we can do const network
name is going to equal that helper
config
at the chain id now typescript is
actually going to get a little bit mad
at us here so we need to add a little
bit more to this line actually so we
need to say okay only grab from this
helper config if chain id exists right
because there might be a chance that
train chain id is nothing or it's
something really weird so we're going to
say chain id i'm going to use this
tertiary tertiary operator again we're
gonna say if this chain id exists
then go ahead and use the helper config
however if it doesn't exist
just use dev i should spell
chain id right so it doesn't get really
confused to me and whenever we return
one of these components or try to use
one of these components we're always
going to have to return some type of
html or div tag like this we head over
to our app
we add our little main bit here
of course we're going to want to import
this say import
main
from
dot slash components
slash main we save it we'll add our
main tag
syntax we're basically saying in it now
depending on your setup you might
actually run into this error here saying
element implicitly has an any type
because expression blah blah blah you
might be saying okay well what's going
on here now to make our lives easier
we're going to tone down typescripts
strictness here so what we're going to
do
is in our typescript config.json we're
actually going to add suppress
implicit
any index errors
so we're basically suppressing when we
get this type of error because it's not
ever actually going to affect anything i
should probably i should probably spell
this correctly we'll save it
now if we save this file here
we're going to actually get this saying
everything's compiled everything looks
good
and if we refresh our front end we're
gonna get back to exactly where we are
before
now what we can also do is we can also
console.log these out we can also see in
the console
exactly what these are gonna look like
so if we do console.log chain id and
console.log network name
we save and we go back we can go hit
inspect
go to the console
and we'll see 42 and coven gets printed
out in the console over here so that's
42 is the chain id and coven is the
is the network name so we know that
we're doing this right okay great
so we have
our network name and we have a chain id
we've got a way for us to update our
front end with a new script let's
finally get those different addresses
that we need say the constant variable
gap token address
is going to equal
something from that build folder or that
chain info folder that we created inside
here inside deployments we have this
map.json
and since i've already deployed this to
coven
we have dap token and token farm on the
cova network so we can then use that and
say
if
if we are connected to a chain id and
that's again that's what this question
mark is doing
saying if this chain id exists
then
look into that mapping else we're just
going to use a zero address right so how
do we actually get this mapping in here
though so i'm going to say import
network
mapping
from
this is going to be in that chain info
folder
inside the deployments
deployments
and it's just going to be map.json
so we're going to take this network
mapping object
and we're going to say if the chain id
exists
then inside this network mapping json
object we're going to
cast
that chain id
as a string
and then we're going to grab
the name of the dab token which is going
to be dap token and we're going to grab
whatever address is at the top right so
this is going to be a big list the more
times we deploy
the more times brown is going to keep
track of it and there's going to be all
these different addresses and we just
want this one right at the top right we
want the most recent one here so we're
just going to say at position zero
otherwise if we're not on a chain id
we're just going to use a zero address
and ether's js actually has a really
nice package to give us what's called
constants so we're going to do
constants
dot
address zero
and we can import that from ethers
so we'll do import
cons
dance
from
ethers
if you don't already have ethers
installed here
we're going to do
cd front end we're going to do yarn add
ethers
and now we have the ethers package in
here now we're not going to do the same
thing for the weft token or the fau
token
because those tokens are defined in the
brownie config as opposed to being
defined in our map.json here so to get
those ones we're going to say const
with token address
it's going to equal let's check first if
the chain id exists and if it does
we're going to grab it from
the brownie config so to grab that
we're going to do
import
brownie config
from
again now that we've imported it
brownie config.json
now we can work with this brownie config
inside of our front end so we'll say
browning config
of networks
of that network name of the
left token and if chain id oops chain id
does not exist then once again
we're gonna do constants dot address
zero so we're just gonna leave it blank
and then we're going to do the exact
same thing for the fau slash the die
token so we'll do const fau
token address
equals chain id question mark
so if the chain id does exist it'll be
the brownie
config
networks
network name
fau token
and if chain id doesn't exist it'll be
constants
dot
address
zero
okay awesome
and if we save it
oops looks like i put in an extra
comment there by accident i'm just gonna
get rid of that and resave
and then refresh here so i'm getting an
issue
uh because i'm on the rink beat chain
right now and it's saying hey there's no
there's nothing for rink there's no dap
token for rink b you gotta be on coven
so if i go back to coven here
and i refresh now it works out fine
right this might still break for you if
you're on coven and you haven't deployed
anything to coven we can fix this in our
config for the dap provider by changing
the supported chains for this now
typically a lot of the times you're
going to want to test using a ganache
chain or some type of local chain so
that your front end testing can be a lot
faster for this we're just going to do
everything on coven but a nice little
challenge for you would be to refactor
this so that it also works with
something like ganache and we're going
to not use ganache so i'm just going to
go back to app.tsx
we're going to remove ganache
even we're going to even remove rink b
for now we're just going to work with
coven just to make it simple if i go to
our react page now
refresh i can connect
awesome
if i go to
ring b it's not going to freak out
because it says hey ring b is not even
supported so i don't care what you're
doing
however covent is supported
so we're connected and we're looking
good and the thing is we really don't
want to couple our front end with our
contracts right we really want to code
the contracts independently and the
front end independently anyways so let's
get back into our
main.tsx because we're going to be in
here for a while but we've already done
some great things we've gotten what
network we're on what chain id we're on
and we've gotten the different addresses
for these different tokens so as you can
probably see
the place that we're actually going to
put stuff on the front end is in this
little return statement here right right
now we're just returning i'm main and we
just see my main right here to do this
we're actually going to make another
component we're going to make a
component called your wallet this
component is going to be a part of this
main component here it's a component
inside of a component that is literally
only going to address our wallet needs
so in our little components tab here
we're going to go ahead and create a new
folder
and we're going to call it your
wallet and this is just going to have
everything to do with our wallet in here
so let's get in here we'll create a new
file because we're going to actually
make a couple files and our first one is
going to be your wallet.tsx
this is going to be our component that
is just going to deal with getting our
wallet getting the token balances of the
different tokens that we have since we
know we're going to put this component
in main and main is in our
our home base our app.tsx you know that
we're going to do an export
const
your wallet
in here and we'll make this a function
now in order to actually show these
tokens we do need to
get some information from our other
component we need to get some
information on what the supported tokens
even are
so we're going to have our main
actually pass a variable
to our wallet here
we're going to call it the supported
tokens
and this is going to be of type
your wallet props
and this is going to be a your wallet
props here just to tell typescript what
this is what this supported tokens is
going to look like we're going to say
interface your wallet props it's going
to look like this
supported tokens
and it's going to be an array
of tokens and array of some token
we're going to grab that token type
from main as well so actually we're
going to do import
token
from
main
and in our main we're going to pass this
token and we're going to pass some
supported tokens to our wallet
so right underneath those three token
addresses
back in main we're going to do const
supported tokens
is going to be an array
of token this token type
so above here
we do export
type token
equals
and we're going to say a token type is
going to involve an image which is going
to be a string
an address which is also going to be a
string
and a name which will also be a string
so we're creating a new type called
token here in our main function
we're creating this supported tokens
object which is an array of tokens and
this is excuse me and this is going to
equal
that array syntax
so our first token
is going to be
have an image
that we haven't defined yet
the address
is going to be
this dap token address
and the
name the name of course is going to be
gap for dap token
now we're going to need a couple images
so at this point you should see where
we're going with this we create this
array of supported tokens
first is our dap token and we need an
image for this dap token so if you're
following along you can just grab this
image right off of the github
and we're going to grab that dab token
and we're going to pop it into src
we're going to change this to
dap.png
now we can import this by doing import
dap from dot dot slash dap dot png
now i can take this dap image
and under image i'll put
now let's do the other tokens so we'll
do a comma we'll do image
we'll be f
oops
f
address will be
weath token
with token address name will be
wef
and again we can either oh and let's
close this off
and again we can either grab right from
my github or pop it into my src here
we'll change this to f dot png we'll
scroll up and we'll import this as well
import f from dot dot slash at that png
and boom that looks good
one more comma image
it's going to be
fau
or
it's going to be our die token
address is going to be fau
token address
name
it's going to be fau
or die
this will be our die token
we'll pop it into our src
change the name to
die dot png no import
die from dot dot slash die dot png
grab die and it looks like we're going
to name it die actually instead and if
your vs code starts yelling at you about
this can't find module it's really
confused what we're going to do at the
top here so we're just going to add a
little comment backslash star eslint
disable
spaced
comment
star backslash
dash dash dash
ref
errant
types
equals react
scripts
and we'll save and that issue will go
away
all right well now that we have
our supported tokens token array we can
actually pass this to
that your wallet bit
right so now we're going to
go to this return bit we're going to
remove that div on main and we're going
to actually start getting to some meat
here so we're going to pass this to our
your wallet component that we're going
to import in just a second
and we're going to send it our
supported tokens let's say supported
tokens equals
supported tokens
backslash like this
and of course we're gonna have to import
your wallet here
so we'll scroll to the top we'll do
import
your wallet
from
dot slash
your
wallet
we're actually going to make a new file
in our your wallet folder called
index.ts
and we're just going to export
your wallet
from dot slash your
wallet
save that
i'm getting an issue
[Music]
saying you wallet it's not defined
it's because this should be your wallet
okay cool so we're getting another issue
but i'm going to fix that in a second
great so now we have some supported
tokens
we have a wallet here
we're exporting our wallet with our
index.ts and our your wallet
folder now let's finish our your wallet
implementation
and this needs a little equal sign here
whoops
and we're going to get this little error
basically because we don't have a return
here
so we could just do return
just to make it happy div
hi
and we'll even change this to i'm your
wallet and we'll save and now
everything's happy we'll go to our front
end we'll do a quick refresh and now we
see i'm your wallet so let's keep diving
into your wallet here right because this
is going to be
where we're doing all of this stuff
about what's in your wallet now we're
going to use a couple of these
components from the materials ui here to
get started
to start we're just going to use this
box the box component it serves just as
a wrapper component for most of the css
utility needs it's
just a box right it's a box that we can
put on our front end so we're going to
come over in into our your wallet and
we'll start working with this box we're
going to put everything
inside
of this little
this little box here
i'm going to import this box
import
box
from
[Music]
at material
ui core
we'll give this a little header
h1 we'll say
your wallet
h1
get a little header your wallet on your
wallet great
now we'll get rid of this little i'm
your wallet and we'll create another box
and in here we're going to add
all of our functionality for
what is in our wallet now we're going to
use some tabs here
from the materials ui
to swap between the tokens right we're
going to have one tab for
fau token another tab for zap token and
for wrapped ether we're going to use
this this this tabs thing here so to
work with tabs we're going to need to
import some
tab stuff so we're going to import
tab context tab list
and tab panel
from
material ui
lab
so material ui
material i slash lab these are some
components that they're not quite ready
to move to the core so we do have to add
these as well so we'll go to our front
end and our other shell and we'll do
yarn add
and material ui
lab these are kind of their testy ones
but they have some really nice features
that we're going to use but let's get
into this box and let's make
our first tab context
value
equal to
now in our box here the first tab
that we're going to have to use is going
to be whatever token that we have
selected
to select tokens we're going to use
what's called a state hook
so we're going to create a state hook
here inside of this
we're going to do
const
selected token index
set selected token index
equals
use
state
number
zero
so use state we're going to grab from
react it looks like i've already
imported here
import react
comma
brackets use state
from react
and what this is going to do it's going
to create one variable select the token
index this is going to be whatever token
that we're on and then set selected
token index is going to update this
selected token index this u state state
components thing is a way of saving
state
between renders of components so in our
little box here
we're going to start with a tab context
we'll start basically with our own tab
and the value is going to be equal to
whatever
token we currently have selected dot to
string
and we're gonna have to make a list of
these tokens in our tab context
we're gonna have to add some way to
change
between the tabs right when we change
between the tabs we want a different
token to be selected and we're going to
make a
tab list that's going to change whenever
we
click the different tab so
we're going to add we're going to add
some functionality to this but for now
we're just going to give it an aria
label
call this our
stake form tabs and based off the
supported
tokens
in a mapping
of token to index
we're going to call a function in here
where we return
a tab
which will have a label equal to the
token.name the value would be equal to
the index
dot string or excuse me dot 2 string
and the key
is going to be equal to
the index
tab is something that is just from the
material ui core so we're going to
import
tab
from
that material
ui core
i should probably spell supported tokens
correctly
supported tokens now
if we look at our ui we can now see
we've got a couple different buttons
here which great we have dap west and
die right these are the different
supported tokens that we're mapping here
now of course if we click the different
buttons
nothing actually happens so we do need
to to handle a change we do need to code
some functionality to handle a change
whenever we do something different so in
our tab list we're going to add on
change
on
change
equals
handle
change
i'm going to code a little functionality
at the top to actually handle a change
so we'll say const
handle change
equal to
an event
a react dot
change event
we'll do a new value
it's gonna be a string
and this is a function
so we're gonna do this little function
syntax again
and all we're going to do is we're going
to use our little state hook here so
we're going to do set
selected
token index
and we're going to parse
the int
of the new value that we get
so what's happening here we've added
this new functionality where whenever we
change
one of those tabs we're going to change
this the selected token right this
selected token number is going to be
different and what we do is we map the
indexes to a token right so each one of
these tokens is going to represent a
certain number so now when we save let
me go check out our front end you can
now see that we do indeed swap between
tabs here which is really nice all right
let's keep going so that's cool we have
a way to swap between the different
tokens visually here but we need a big
stake button right the reason that we
need to swap between the tokens is
because we need a way to stake
between them
so when we're on one of these tabs we're
going to add a stake form here we're
going to add a big button that allows us
to stake so we're going to do some
typescript we're going to do supported
tokens.map
i'm going to map that token and index
again
function use that and then here we're
going to return
a different tab panel
the value in here is going to be the
index
dot to string
key is gonna be
the index
we'll make a little div in here
and we're gonna need to put two pieces
in here we're gonna need to be putting
our wallet balance in here and then also
a big
stake button right
of course we're looking at right now
it's just going to say our wallet
balance and a big stake button but how
do we actually do this how do we
actually get our wallet balance and one
of these big stake buttons
well we're probably going to need some
type of component to get our actual
wallet balance that we're going to stick
in here
so yup you already know we're going to
go in here into our your wallet
component we're going to create a new
file and this is where we're going to
define
that wallet balance component and we're
going to import our wallet balance
into our wallet here so that we can
actually see
the balance of our wallet right in the
front end and right and this is where
we're going to actually be reading off
chain finally after a lot of typescript
and react setup since we're going to be
importing this into our your wallet
component here of course we're going to
start with export const
wallet balance
we're going to make this a function so
we'll do this
really weird
function syntax and we're probably going
to want to pass this
the token right the token that we want
to get the balance of
so we're even going to set that up like
this a token in here
and we'll define
what this looks like uh with the
interface called wallet balance props so
we'll say export interface
wallet balance props
and this will be
a token right
this will be that same
token type that we defined before so
we're gonna have to import that so we'll
say import
token
from
[Music]
main
all right great that's our initial setup
here we'll grab
from the token that we passed to this
we'll pass we'll get the image
address
and the name
from that token
address and name
we'll grab the account right because
we're going to need the account with
along with the token
so we'll say const
account
equals use ethers
and of course
we're gonna have to import
account
from
excuse me imports not account use
ethers
from at use dap
slash core
we're gonna need the account we're gonna
need the address and use dab core has a
nice little hook
called
use token balance that we're going to
use you look check it out in the
documentation provides a way to fetch
the balance of erc20 tokens specified by
a token address it makes our lives a lot
easier so we'll just import that as well
use
token balance and all we have to do
really is do const
token balance
equals
use
token balance
of the address of the token
and our count here we can even do a
quick console.log
token balance
see if we're doing it correctly and we
take this wallet balance and import it
into our wallet here
we should be able to see
something so we'll import it into our
wallet now let's go into the top we'll
do
import wallet
balance from
dot slash
wallet balance and down inside our very
large return function here we'll add
this new
tab
or this new uh component we'll say
wallet balance
we still remember we need to send it the
token
so we'll send it
tokens
at the index of the selected
token index
i should spell supported tokens right
i should spell wallet balance right
capital b we do need to do a return
so that it's actually a jsx component
we'll do a div
we'll just have to say i'm the wallet
balance if we go to our front end we do
a quick refresh
we do indeed see this little print line
here uh this is javascript's big number
so if we really want to see this token
balance we'll do dot to string
and we have to put this question mark
here to tell typescript hey
turn it to a string if it's not
undefined and now if we save we go to
our front end
we do a refresh
since we are connected
to coven here we can see
we get an amount printed out here and if
we switch tabs
you'll see
the different amounts being printed here
which is fantastic cool so let's remove
this little console.log we want to show
this token balance obviously in our ui
right we don't want to have people to
have to go to the console.log right to
actually see it we want it to represent
we want to show up where it says i'm the
wallet balance so what we're gonna do
first we should probably format it
right because this is in units of way
so we're gonna do const
formatted
token balance
this will be a number which will equal
to
token balance
if token balance does exist
again we're using this tertiary operator
we're going to parse
float
format
units
balance
18
otherwise we're just going to use zero
format units is a nice little import
that we're going to grab from
the ethers project so we'll do import
format units
from at ether's project
slash
units
and of course
yarn add at ethers project and of course
we're going to do a yarn add on this
here we'll do yarn add
at ether's project units and now this
formatted token balance is going to be
this token balance that we just got but
formatted formatted much nicer in our
little div here what we could just do so
we could just add this formatted token
balance
we'll save and we'll look at the front
end now
and aha
we now see we have 100 dapp zero weft
and 15 die right these numbers might be
a little bit different depending on how
much you actually got but this is
perfect this is exactly what we're
looking for so let's close out the
console and
let's let's flesh this out a little bit
let's make this look a little bit nicer
here so instead of just returning a
little div like this let's actually make
a new component called
balance message
and we'll use this instead
create a new component called balance
message and it'll format up the way we
actually show these formatted tokens and
here we'll pass
we'll pass it
a couple variables we'll pass this
component an amount we'll pass it a
label
we'll say the label is going to be
your unstaked
name
balance
right we're grabbing name from the token
and we'll pass it a token image src
which is going to be that image so we're
going to pass it a label
or excuse me not img it's going to be
image we're going to pass it a label
token image and an amount right and this
component is just going to make us
have this balance look a little bit
nicer so in our our your wallet section
i'm going to do a new file
called balance message.tsx oops not tsx
tsx and we can kind of rip through this
pretty quickly so per usual we're going
to export
const
balance message is gonna equal
a function where it's gonna take those
parameters a label
and a mount
and a token image
src and this will be
an interface of balance message props
this will be a function of course so
we'll do this weird
function syntax of course we need to
tell typescript
what this looks like so we'll say
interface
balance message props
what are those inputs
we'll say the label
is going to be a string
the amount
it's going to be a number
and the token image src
is going to be a string and in here
we're going to use
and in here we're going to once again do
that use styles bit for materials ui
because we want to style this up a
little bit so we're going to import make
styles
from
[Music]
at material
slash ui core
we'll do a const use styles
it's going to equal make styles
theme which we're going to skip doing a
theme but let's make some styles for the
different pieces let's give it balance
message be surrounded mainly by a
container
which will have a couple of styles in
here we'll say the display
it's going to be an inline grid the grid
template columns
are going to be
auto auto auto again you can check out
all these parameters in the
documentation
there's going to be a gap which will be
theme dot spacing
one again we're skipping theme but this
will just be a way to add some spacing
and then align items
in the center we'll also give
token image
its own
styling we give it a width
of 32px
32 pixels and then
the amount
just do
we go to font weight
of 700. so we'll make that a a little
thick
so now that we have our use styles we
have our styling here we can go into our
export below
we'll do const classes
equals
use styles
and we're going to return we're going to
return a div
class name is going to be equal to that
main container
classes.container
we'll do another div just for that label
that we're looking for we'll do another
div
for class name
equals
classes dot amount
so have that that nice font weight and
then here we'll just have the
amount
and then we'll grab that image of the
token
class name is going to equal to
classes dot token image
we'll grab the source of that image is
just going to be that token image src
that we get passed
and we'll give it an alt
called token logo
and we'll close that tab out
great so we're going to want to do is in
our wallet balance here it's balance
message that we just created we'll do
import
balance message
from dot
dot com
mints slash
your wallet
capital w and actually i know we're
going to use this balance message a
little bit later so i'm actually going
to grab it
and drag it into components move it into
components and move it out of your
wallet
because i know that we're actually going
to use it a little bit later so that
means in our wallet balance
we're just going to pull it right from
components
slash
balance message
and whoops we actually need to make this
look like
this
close it out here
remove this part
like this boom right like that
and now let's try out the front end okay
we're looking a little bit nicer
right we have a really thick number here
explaining how much of the token we have
we have the images popping up this looks
starting to look great let's add this
stake button right so that when they see
this they can actually stake and
interact with our contract here so to do
this we do need to create another
component called our stake form so in
your wallet we're going to create a new
file
called stake form dot ts x and this is
where we're going to add
a little button
and an amount for the users to actually
stake on our contract so you already
know we're going to start with export
const
state form
equals
and we're going to have
our wallet pass
the token just like we passed the token
to wallet balance
so we'll say token and we'll have this
be stake form props
which is an interface we're going to
define in a second this is a function so
we'll do this fun function
syntax here
and then stake form props as you know is
just going to be a token so do inter
export
interface
stake form
[Music]
props
this is just going to be a token of type
token which again
we're going to import token
from
maine
great and that is our starting point for
this so we're going to create a stake
form
with a big button that says stake and
the user can actually choose how much
they want to stake on our smart contract
so we're going to do some similar stuff
as we did before we're going to grab
some variables we're going to say the
address is going to be that token
address
that we get from the pass token
we're also going to get a name
of the token
from that token
we're going to get our account
from use ethers again
so we can import that we'll say from or
oops
import
use ethers
from
at use
dap slash core we're going to want to
grab the token balance so we'll do const
token balance
once again we can grab that with the use
token balance with the token address
and the account
so we're going to use use token balance
this will also grab from used app slash
core we're going to want to format this
token balance so we'll do const
format it token
balance it's going to be a number
again this is going to be the exact same
as we did before say token balance
do parse float
format units
token balance
18
or
zero
in format units once again we're going
to import that import
format units from
at ether's project slash units
perfect
importing here we've gotten some some
starter boilerplate let's just go ahead
and grab those buttons right because
those are really the things that we're
going to care about here let's just
return some stuff here so something can
show up on our front end right so let's
do return
i'll start returning something here and
whenever we return something it's all
gonna be in one
tag right so i'm gonna i know i'm gonna
be doing a whole bunch of different tags
so i'm just gonna go ahead and make an
open and close tag here
and this is where i'm going to put all
my stuff now we know we're going to want
to have a big stake button right so
let's go ahead and just do
let's get a let's get a button tag in
here and of course since we're going to
have a button
we're going to pull this in
from that materials eye material ui
right so we'll do import
button
from
material
ui core just so we can get get started
with something here and then back in our
your wallet.tsx let's add this button in
here inside of our tab panel
right below our wallet balance we'll add
this
stake form thing we'll open and close of
course we've got to import it
so we'll say import
stake form from
dot slash
stake form and
we need to pass this that token object
so back in our your wallet we're gonna
say okay token
equals
supported tokens
of that
selected token
index
selected
token
index and let's not have this
let's just do a little backslash here to
close that out let's be sure to close
this bracket here we'll give this button
some stuff right we'll do color equals
primary say size equals large then we'll
give it some text called
stake
double exclamation point or however many
you want to put in there and now if we
look at the front we got this big stake
button
nice okay we're looking a little bit
better currently doesn't do anything but
we have a stake button great
now we can start adding some
implementation right we can have it do
some stuff now
when we hit this stake button what do we
want it to do we want to do two things
we want to approve
whatever token that we have and then we
want it to stake that amount we also
need to have some type of form here we
need to know how much we want to stake
right so we're going to need some little
input box that we can add a certain
amount in well we can do that too with a
little input box from materials ui so
there's another package we're going to
grab which is called input
from materials ui core
and then we're going to use this little
input box before
the button so we're gonna do input
little slash here now if we save
refresh the front end
awesome now we can do some typing in
here we can click this stake button now
to do this though we're gonna need to
keep track of how much amount is in here
right we're going to need to keep track
of how much amount's in here
so we're going to inspect on the front
end and we're going to go to console and
see if we can follow along
with how much is in here or what amount
is in here and to do this we're going to
make another one of those state hooks
and we're going to track that amount in
there
so we're going to say const
amount
set amount
for one of these stakeholders equals use
state which is going to be a number
or a string or an array number or string
zero
and we're going to import this use state
here
from react so we're going to do import
import
react
use state
from react
and now we have this state hook that we
can use to keep track of the amount
that's going to be put in there with our
input tag here we're going to say on
change
whenever this changes we're going to
have to
have some handle function right we're
going to call it
handle
input change and this is going to handle
the input change so we're going to
create that function we're going to do
const
handle input change equals and we're
going to use some event stuff in here
we're going to say this is going to take
an event
a react
dot change
event
of html input element
this is going to be a function
that's going to
set amount
it's going to say
const
new amount
equals
event.target.value
whenever we change that value in that
field if if it's equal to nothing
then we're just going to say okay we're
going to do nothing
otherwise
we're going to cast it as a number
event.target.value
we're going to cast whatever is in there
as a number
and then
we're going to do set amount
to this new amount what we could do is
we can even do a console.log
new amount
and now and we can start using it right
so if i go back here and do one two
three right you can see it's
console.logging every time i change
something in here so now we have a way
to actually get that amount with this
input now we're going to need to weigh
to send that amount as part of our stake
right so we're going to first have to
call that approve function with this
amount and then we're going to have to
call
from our token farm then we're going to
have to call the stake method so how do
we get
it to call this approve function here
well to do these we're actually going to
make some new state hooks that we're
going to use in our staking form here
we're going to make state hooks for
approving and for staking and even for
unstaking so
back in our folder here we're going to
create a new folder
called hooks
and this is where we're going to add
some different hooks
first hook that we're going to make is
going to be called use
use stake
tokens dot type script and this is
something that we're going to import
into our our stake form here so we can
actually stake some tokens and the way
we want to do it too
is that once we hit stake once we hit
our stake button
it kicks off the approve and then and
actually right afterwards it kicks off
ascend it kicks off a stake token we
want to run these two
functions sequentially and we're going
to make this use stake token hook clever
enough to do it in that order so let's
do it hooks are basically just like
components except for they're more
functionality wise so since we know
we're just like components we're going
to do export const
use stake tokens and this is going to be
a function
just like our other components and as
input we're going to take a token
address
that's going to be a string and inside
of this we're going to have some
intelligent scripts to know if it's
already been approved if it's not
already been approved and what we need
to do right we know we're going to need
some approved thing and we know we're
going to need some stake tokens thing so
let's let's at least try to approach
this approved thing first before we get
too creative right how do we approve
this transaction to get an approve we're
going to need a couple things we're
going to need the address
as you guys know
we're probably going to need the abi
we're probably going to need
the chain id so we know which chain it's
on
so let's go ahead and let's grab those
so we'll do const chain id
equals use ethers
and since we're using use ethers here
we're going to import this so we'll do
import
use ethers
from at use dep
slash core
we're also going to want the abi of the
token farm so we'll do const
abi
equals well where do we get this api
from ha that's right we've imported it
in our little chain info piece and
should be right in here we could should
be able to do
import
token farm
from down to directory it'll be in
chain info slash contracts
slash
tokenfarm.json and now we can say
avi is going to be equal to this this
token farm right because in token farm
we have an abi key so we can just
abstract that away and just pull out the
api perfect we're going to need the
token address of course we're also going
to need our token farm address and we
can find that the exact same way we
found it before
with const token farm
address
it's going to be equal to
depending on if the chain id exists
once again we're going to want to use
that network mapping so we can even go
back to main.tsx
let's see how we did it here for the
depth token address
you can copy this as like a frame of
reference
we'll say if this chain id exists we'll
pull
right from that network mapping
right we'll pull right from the network
mapping so we got to import that too
which we can grab from
import
network mapping
from
chain
info chain info slash
deployments
slash
map.json so once again we're going to
say if that chain id exists
in the network mapping
we're going to use
that string chain id
so we'll do string
chain id
of
the token farm
at position 0 right because we obviously
want the most recent one otherwise again
we'll do constants dot
address
zero
and since we're going to do that of
course we're gonna have to do import
constants
from
[Music]
ethers
and this hooks folder should be in
source so let's just make sure that
we have hooks in source here now we're
going to want to interact with this
token farm address contract right we're
going to want to run that proof function
first we want to create like an
interface so we can do const
token farm interface we'll say this
equals new
utils.interface with the abi
this utils we can again grab from the
ethers project or excuse me from uh from
ethers so we'll do comma utils
now we can create a token form interface
here and now that we have interface
we'll create a contract so we'll do
const token farm contract
equals new
contract
and this will be a combination of this
token farm interface and the token farm
address actually it's address first and
contract is something we can grab from
import
contract from at ether's project
slash
contracts
all right
you're probably starting to follow along
and figure out okay cool i have a token
farm contract
now that we have a contract we can
actually call some functions which we
totally can but right we need to call
the approve first so let's get
the token contract before we even work
with the stake token right so to work
with the token we're going to want to do
the same thing so we'll do const
erc20
interface
equals new utils dot interface
interface
and this will be from ear c20
abi which we should probably make first
so we'll do const erc20 avi
equals
we'll do it the same way we did up here
except for instead of token farm we'll
do something else we'll do
look in our contracts here
we'll do mock erc20 instead
and then we'll just call this erc20
or yeah we'll just call this erc20
but we'll grab it from our mock erc20
dot json
so now that we have the crc20 we do
const erc20 api equals
erc20.avi
and we can just pop this api
to create our interface we'll now do
const erc20
contract
equals new contract of
the token address
comma the erc20 interface
boom okay
now we have both of these contracts we
have the erc20 contract we have the
token farm contract now we should be
able to go ahead and call some functions
right now to actually send one of these
we're going to use this thing called use
contract function it's a hook in use dap
that returns an object with two
variables a state and a send this state
bit is used to represent the status of
the transaction and that's how we're
actually going to automatically kick off
the stake after we approve to send a
transaction we have to actually have to
we actually have to use this send
function here
so we're going to use this use contract
function to get to get a state and
ascend so that's what we're going to
first need to do so we're going to const
send
and then we're going to call this
approve erc
20 send
and state because this is what it's
returning it's returning send an estate
i'm going to say state is going to be
approved
erc20 state
equals
use contract function
we pass the token contract the erc20
contract
comma the name of the function which is
going to be approve
then we do a comma and then we'll do a
little object here we'll call this
transaction name
and this will just be approve
erc20
transfer
then of course i have to import this
from used app this use contract function
now oddly enough
oops i got rid of the
closing tag here but great so now in a
weird way we actually have these two
new pieces here we have this send
function this approve vrc20 send
and this approve erc20 state this is
going to be
the status of our transaction and this
is going to be the actual function that
we use and if we want to call this
approve function what we can do
is now we can return calling this proof
function so we'll do const approve
we'll have this be
a function we'll say it'll take a string
amount as an input parameter
and we'll just have it return
this approve erc20 send and we'll give
it the token
farm
contract address
as a first input parameter excuse me
token farm address and we'll use this
input amount as the second parameter and
then we'll just have this
this use stake tokens return this
approve function
and then also
this state here so it's going to return
approve
and it's going to return state we could
also just have it return this if we
wanted
but we're going to wrap it just all up
in this approved thing here we also
probably want to return this state right
so we're going to turn this into
hook as well
so we're gonna do const
state
set state
equals
oops
use state and we'll have this be the
approved
or the approved erc 20
state
as the input and of course since we're
using use state we're going to grab this
from react as well we also want to
return the state so we'll return this
approve erc20 state here so now we have
a way
to actually do all this
so in our stake form
what we're going to have
is we're going to create const that's
going to grab those two variables so
we'll do const approve
and approve erc20 state is going to be
equal to use
stake tokens
with that token
address
pulled down from the token as the input
parameter
and this is our new hook so we're going
to import
use stake tokens
from
dot dot slash dot dot slash hooks now
that we have these two functions we have
the approve function and then we have
the state of that function
now we can add a handle submit
functionality for our button here
so now we can say okay on click
when we click this button
we're gonna do
a handle
stake
submit
right because this is that our big well
it's not gonna show up now because i
broke everything but this is our big
button right this is our this is our
stake button so we're going to create
this function called handle stake submit
let's go ahead and do const
handle stake submit
this will be a function
and what it's going to do
is we'll get this amount here so we'll
do const
amount
which we're going to actually have to
convert it from
string to way so we'll call it amount as
way
we'll do equals utils.parse
ether we'll grab parse ether
we'll grab utils
again from ethers
utils from
ethers
and we'll do the amount dot 2 string
so we're going to grab this amount this
statehook amount here we'll turn it into
a string
and then what we can do is we can return
this approve function
with this amount as way
okay oh and then we're getting a fail to
compile so in our hooks section we're
just gonna do an index.typescript
and we're gonna export this use stake
so we'll do export
use
stake tokens
from dot slash use stake
tokens
close that
we'll restart the server
and then i should import this from the
right place
and i should import this from the right
place as well
and let's get rid of the brackets here
whoops sorry
and let's do this
as a dot to string oops because you
can't do a big number
now let's save it'll recompile we'll pop
into our front end here we'll do a
refresh
our stuff is up that's cool our stuff is
getting
logged out now if we hit stake
we should call the approve function here
metamask pops up we do get allow
localhost to spend your dap this is
amazing we're gonna reject this for now
though because
or don't want to bother testing it so
amazing job getting this far we're
hitting a button
metamask is popping up and
we're doing it we're actually sending a
transaction this is incredibly exciting
great work so far let's keep going uh
the approve function is working
perfectly it's working as intended or
we're just we're kind of assuming it's
working as intended but that's great
this is perfect so now we've got to go
one step further we need to have this
call stake after it's been approved this
is where we're going to do a little
something called use effect we can
import in here
just to use effect
comma what use effect does it allows us
to do something if some variable has
changed
so the way that we're going to do that
is we're going to say okay
use effect
and it takes one of these functions as
an input and then we'll do a little
comma here and similar to those state
hooks we'll do an array
of different things we want to track and
if anything in this array changes we'll
kick off this use effect and we'll do
something in here
so one of these things that we
definitely want to
track is this approved erc20 state
if approved erc20 state if this
transaction comes back successful
then we want to do some stuff
so we'll say we'll track this
this state and we'll go ahead and say if
approve erc20 state dot status
equals
success
then
we're going to go ahead and do like a
stake function
and to do a state function we're going
to follow this exact same methodology
that we did for the approve
so first
we're going to use this use contract
function thing
so we'll do const
send is going to be
stake
send
and then state
will be
stake state
this is going to be equal to
again we're going to use use contract
function
this is going to be on our
token farm
contract this is going to be our stake
tokens
function
and this will be trans action name it's
just going to be stake tokens
and that's it
so let's make this look a little bit
more readable here lovely
so we have our little used contract bit
here and now this stake send we can just
call this right in this approve erc20
dot state does status we need to do
stake send
and if we look back in our token farm if
we do stake
tokens we have an amount and a token
address so that's what we're going to
have to put in here
we have to put some amount
and then token address will just be
token address
where do we actually get this amount
from
well when we originally called
this approved function this is when we
should actually do it and you might be
asking hey
how come we wrapped this approve your
c20 into a function here but we're not
going to do that here i'll tell you why
in just a second so what we're going to
have is we're going to have a state hook
for how much we want to actually
stake so we'll do const
amount to stake
and set amount to stake
it's going to be equal to use state
and we're going to start with zero we're
just going to get this defaulted right
to zero
and what we're going to do actually
is once we call this approve function
the first time
we're going to set amount to stake
to be
this amount and what we should do
instead of calling this approve is we
should call this approve
and stake
since it's this function that's going to
kick off yes it's going to kick off our
approve erc20
but it's also going to change
the amount that we're going to stake
and later on
once the transaction succeeds it will
also then kick off our steak send
or our staking function so we're going
to change this to a proven stake that
means below we have to actually return a
proven stake and not just approve
and for stake send the amount is going
to be this
amount to stake which we got from our
original proven stake and then we just
have to change this to approve
and stake
and we'll change this from improve to
approve and stake and realistically
that's all we really need to do here so
if we save we go back to our front end
let's go to one of these that i actually
have some of i'll type in one
for in here i'll hit the stake button
and what should happen is approve will
come up i'll confirm
and once this actually confirms then
i'll be able to another transaction
should pop up
telling us
to actually stake and that's exactly
what happens here so we've approved now
we can stake we'll even watch metamask
really really quick here i'm doing this
on coven
right i just called this state tokens
function
for those of you doing this on ganache
will be a lot quicker but perfect that
was fantastic our balance even got
deducted by one now we have
one
of these tokens actually staked and this
is fantastic however
there's obviously a couple issues here
right
what was happening during that that
whole section right there is there was
no indication for us of what was really
going on got no notifications we're
totally left in the dark here
additionally
this page still looks disgusting so we
want to clean this up we want to make
this look a lot nicer so how can we
actually do this
so for switching between these we want
to actually just change our use effect
here
so we do want to check let's approve
erc20 state but we also want to see if
we switch the token address
we want to just check to see if approve
vrc20 is done if we switch our token
address
and we also want to just check to see
this if amount to stake actually changes
so if we do amount to
stake
we want to check kind of during all
these these three if any of these three
changes we'll just do a quick check hey
is the prove vrc20 done if yes great
then we'll we'll stake some tokens so
this is great but we're going to want to
get some notifications that these
transactions are going through these
transactions are pending
and these transactions finish so why do
we actually add those pieces to this
well used app has this thing called use
notifications this notifications bit
will help us actually get notified on
whether or not our transactions are
completing so to use these notifications
we're going to do a couple of different
things in here first all the way back in
our app.tsx we're actually going to
change our config here
we're going to add some notifications
in here
to check periodically if our things are
done
and there's a couple of different
parameters there's a
x
variation period and then we'll set it
to be 1000 this is in milliseconds so
we'll set it to be a thousand which is
just one second
and we'll do a check interval
also of one thousand so basically we're
saying hey every second check the
blockchain on our transactions that we
send please thank you and now that we
have this notifications bit identified
in our staking form
we can add this bit so from used up
decor we'll do comma use notifications
and now we can actually start using some
of these notifications so right here at
the top
we'll do const
notifications
equals use notifications
we can actually start working
with some of these notifications now
we're going to want to see if anything
in any of these notifications actually
change and if these notifications change
we're going to want to do something so
since we're going to want to check to
see if this if notification changes
those who have been following along with
what i've been explaining for use effect
you know that means we're going to want
to use a use effect we're going to say
use effect
it's going to be this function
and if we don't have it imported let's
go ahead and import this from react
let's use effect
we're going to be looking to see if
these notifications change we're going
to be looking to see if our transaction
has completed so in our little watching
array here
we're going to say let's watch the
notifications here let's make sure
if any of those notifications changes if
anything in our meta mask changes we're
going to want to do something right so
we're going to say
if
there are any notifications that are
approved erc20 or transaction succeeded
we want to show hey you know good job
it's been approved
so to do this we're going to say if
notifications
dot
filter
all right this is going to be a function
based off the notification
on this notification we're going to say
notification.type
it's going to be
transaction dot succeeded
succeed
and
that
notification dot transaction name then
this is why we need to give them names
before
in our use state
it's going to be approve
erc20 transfer
dot length
is greater than zero
then we're going to do some stuff
our transaction succeed
so we're saying if
in these notifications we're going to
filter on a notification
if the type is transaction succeeded and
the name is approved erc20 transfer then
we're going to do some stuff and for now
we're just going to do console.log
approved
we can also then do the same thing for
if
notifications dot filter
author on the notification
notification dot type
if that notification to type is going to
be again that transaction
succeed
and
notification
dot transaction name
equals stake
tokens capital t
stake tokens
there are more than one dot length
is greater than zero
then
we'll do console.log
tokens staked
okay so we've got some notifications put
in
we're gonna do a little console logging
let's see if our use effect stuff is
actually gonna work so let's go to our
front end we'll do a quick refresh
we'll go to where we have some tokens
i'm gonna type one in here i'm gonna hit
stake
i'm gonna hit
confirm and we're gonna wait a little
bit and if this confirms correctly
then we're gonna see a little
console.log printout that says approved
and we do indeed and that's perfect
metamask pops up again for our stake
tokens
we hit approve there as well
and we should see a little console.log
out here for state token staked and we
do perfect so now we have a way to
actually track some of these
notifications and track what actually
happens on the blockchain
console.logging stuff is great but we
want to actually see it in our ui here
what we're going to want to do is show a
little waiting thing here
while we're waiting for it to be
approved and then she'll pop up when it
actually does get approved we can add a
little
constant called is mining
which will be based off of whether or
not the transactions are approved so
we'll do const
is mining
and this will be equal to
the state of these transactions so this
should actually instead be approved
erc20 there should be approve
and stake erc20 state now we'll say oops
now we'll say is mining will be equal
to approve and stake erc20 state dot
status
equals equals equals
mining should probably have it look like
this
then back in our
use stake instead of
approve your c20 i'm going to change
this to approve and stake your c20 state
and then we're also going to return
prove and stake erc20 stake
let's make this make a little bit more
sense here get that little red line to
go away and now what we can do with this
is mining thing is we can add this to
our button now we have this is mining
thing it's gonna be based off of whether
or not approve and stake are done so we
can scroll down to our button
and we can add a little disabled flag so
we'll say disabled
equals
it'll be equal to dependent on whether
or not it's done we'll just add is
mining
and if this is true then disabled will
be true and if this isn't mining then
this will be false
we can also add
this to be kind of like a little loading
thing so instead of just saying stake
all the time
we'll do a tertiary operator we'll say
if it is mining
then we'll do like a little loading
thing material ui has this thing called
circular progress that we can use it's
like a little loading thing
so we can do if it is mining we'll do a
circular progress
we'll say the size is 26 or whatever we
want it to be
we'll close the tag out
and if it's not mining again we'll do
this stake with a bunch of exclamation
marks here so now if we save that go to
our front end
it looks like i need to fix something
can't find name approve your c20 state
that's because we changed it this is now
a proven stake er20 state
so let's change it to that
now let's save go back to the front end
and okay cool
let's go to one of these that we have
some stuff with we have a little dial
we'll do one here
we'll hit stake and if we did this right
this should show a little loading thing
while the transaction is going through
so we're gonna hit approve
and perfect we do see a little loading
thing and it should stay like this
until the transaction finishes
this is a good way to indicate to the
user that we've actually
approved
now i'll hit confirm for staking so we
didn't actually see the loading thing go
back up again so this probably means
that we didn't actually reload this is
mining correctly
and the reason we don't see the little
spinny thing is because this a proven
stake erc20 state is really only
tracking the approve right we have our
cost a proven stake which does all this
good stuff here but our staking part
this stake state we actually never use
right and we need to pass this back to
our our stake form so it can actually
know you know what's going on so what we
can do is we can add a new state hook
we'll do const we'll just call this one
state
and then we'll do set state it's going
to be equal
to
use state
and this will be that
approve in stake ear c20 state
we'll start it off there and this will
represent kind of the overall state
right for this will be the true proven
stake ear c20 state
what we're going to do now is we're
going to have to track those both of
those states we're going to track both
the proving and the staking so we're
going to do use effect and we're going
to track both of those
with our little
our little wonderful
use effect stuff so we're going to track
them with by doing of course
proven stake erc20 state and then
stake state so if either one of these
change now we're going to want to change
this overall state function and that is
going to get pushed back to our our
stake form here so what we're going to
say is we're going to say if proven
stake erc20 state dot status
equals equals equals
success
then
we're going to set state to be the stake
state
otherwise we're going to set this
overall state we're going to do set
state
to be this approve and stake bit
or just or really just kind of approve
here now we're going to pass this just
kind of overall state variable here
to our front end like this
excuse me to our stake form and in our
stake form we're just going to say we're
just going to map this state variable to
the proven stake erc20 state we'll save
here that should work perfectly great
now if we go back to our front end we'll
go to die or whatever we'll do one we'll
hit stake
metamask will pop up we'll confirm we do
indeed get this little loading thing
which is perfect once it's done once
it's approved we'll confirm again and we
get loading again and this is perfect
this is exactly what we want because now
the user has a good idea ah okay i need
to wait right the transaction is going
through the transaction is being built
and once it's done
it's all set so this is fantastic we now
have basically all the functionality for
staking right we have a proof we have it
doing some waiting we have it actually
staking
let's clean this up a little bit right
let's make this look a little bit nicer
so first we're gonna go to index.css
we're gonna we're gonna add some bits in
here for a body we're just going to do
background
color we're going to set this to
set a background color
to
[Music]
hsl we'll do 227 comma 61 percent
26 there's a whole bunch of tools the
background color doesn't really matter
but we'll save we'll refresh our front
end and we'll get a nice little uh
background color here which is cool but
let's actually be even more creative
than just this let's do a nice little
linear gradient in here we'll just get
rid of this actually we'll do background
do lin ear
gradient
we'll do 135
right here do hsl 227
61 percent
comma 13 percent
then we'll do hsl 227 61
26
we'll do one more we'll do hsl again
this will be 227
61
39
for some colors in here semicolon there
let's look at our front and k we're
getting somewhere we got some cool
double gradients going on in here we'll
go to our main section here and we'll do
that use styles bits again so right in
our looks like we don't have any
material ui in here so we'll do a little
import
make styles
from
at material
dash ui dash core
and right at the top
we'll do const use styles
equals make
styles
some theme which we're ignoring
nice little function thing here let's
then for our titles in here we'll do a
little
make the color be theme dot
palette dot common dot white which again
we're ignoring theme but if we did
everything we would do like that we'll
do text align
center do some padding
[Music]
theme.spacing4
and then our main of course we'll just
add this in here const
classes equals use
styles
and then we'll just put like a little
little section in here
do an h2
or class name it's going to be equal
to classes.title
and we'll just call this dap
token
app
we'll go back to the front end we got
like a nice little deck token dap token
app nice white right at the top that
looks good we'll go to our your wallet
component we'll add some styles in here
looks like we don't have any styles in
here so we'll do the same thing we'll
grab
make styles in here
do a little const
use styles equals make styles
a theme that we're going to ignore
some fun little function syntax stuff
here
we'll say tab content
give this some styling we'll say all the
tab content stuff we'll have
display of flex
flex direct
sean will be
column
[Music]
align items in the center
and then we'll do a gap for this which
will be
theme.spacing04
give our boxes some stuff so we'll say
box
we'll say
background color is going to be white
we'll say border
radius it's going to be 25 px
to give it some roundness here
then we'll also do a header
which we'll just do color of white
we're going to grab tab content
scroll down
this is going to be inside this little
tab panel bit here
this div
it's gonna have class name
equals
classes dot
tab content
oops we gotta add classes in here right
before the return
so do const
classes equals that use styles
we'll say this box
well it's not we're not going to do the
overarching box this could actually just
be this if we wanted to we'll just say
it's this first box so this will be
class name
equals
classes dot box
and then our h1 is going to be class
name
equals
classes.header
let's save it and let's take a look
whoa
this is already starting to look a lot
better now as you guys can kind of see
the functionality is really the
important part behind the application
and doing a lot of this use style stuff
is what's really going to make it look a
lot prettier right so if you're like hey
how do i do this pretty stuff now i know
i didn't really explain what any of this
pretty
prettiness was doing
there's a ton of tutorials on doing css
that's basically what this is that you
guys can learn a little bit more to make
your stuff look pretty now it looks like
for the most part we have everything
that we need to stay i know we have the
spinning wheel which is great but let's
also add a little bit of an alert at the
bottom to say hey your transaction has
gone through successfully
so what we're going to do
is we're going to pop back over to our
stake form we're going to wrap
our input and our button into their own
little div here right and that is going
to
put a little bit of space actually
between
our little component here and some other
stuff which is kind of nice
but what we're going to do is the reason
that we're doing this is so that we can
add some alerts this section down here
is where we're going to add some
alerting
to do that we're going to use what's
called a snack bar
and alerts from material ui
you can look at both of these
in the documentation
provides a brief message about app
processes and something like this like
we're just going to say hey you did it
transactions has come through
so what we're going to do is we're going
to import snack bar from material ui
so we're going to do comma
snack bar we're also going to import
alerting
like a little alert box import
alert from
at material
ui lab slash alert and what this is
going to do is it's also going to make
these alerts basically down below our
button and our input we're going to do a
little
little snack bar in here
snack bar and we're going to say this is
going to open when we want to show that
the erc20 is done which we're not
exactly sure how to do that quite yet
we'll have it auto hide
auto hide
duration it's gonna be equal to
about five seconds or five thousand
milliseconds and then on close
we're also going to do some stuff
inside this little snack bar
yes i know we haven't filled this out
yet
actually let's just do this for now
having blanks for now
inside the snack bar
we're going to have some alerts
where we say on close
we're also going to do some stuff
severity is going to be
success
and this alert
is what's going to have our text in here
so we'll say erc
20
token
transfer approved
now approve
the second
transaction
and we're going to have two of these
little snack bars one is gonna be for
the erc20
and one is going to be for staking token
so we're going to call this one
token staked
or excuse me tokens staked
now we need to define when these open
and also
when they close and what to do when they
close
so
this erc20 thing should pop up when
erc20 has been approved so we're going
to want to create
some variable that's going to track
whether or not it's actually been
approved so we'll create another state
hook here
we'll do const
show
erc20
approval
success comma set show
erc20 approval success this is going to
be equal to
use state and we're going to start with
false right we don't want to show this
thing right away
and then we're going to want to do the
same thing for staking tokens so we'll
do const
show
stake
token success
and then set
stake token
success
and this will be also used
and we will start this out with false
and what we're going to do
is right now we're doing this
console.login here right and this is
cute
but we want to actually turn this into
changing show erc20 approval success
right so when this actually goes through
when notification says hey it's been
approved we want to say okay great show
that approval status
so instead of doing console.log here
we're going to say set show
your c
20 approval
success to true
and then we're also going to set show
stake
token success
tokens success
to false
i hopefully i'm spelling this right
set
show
stake token success and let's
make sure that's spelled right
great
and then we're going to do the same
thing but the opposite for staking token
so get rid of console.log
we'll do set show erc 20 approval
success to false and set show stake
erc20 to true
now we'll say the erc21 is going to open
and now we can also have this
notifications thing
track
these two
if these ever change
we'll also run through this
so we'll grab both of these in here so
this use effect will now track these as
well and we'll say show erc20 approval
status will open up
the erc20 alert
and then the show state token success
will open up
the state tokens alert and then for both
of these we'll add a new function called
handle close snack
which will just close it out
and turn those
variables that we just made to false so
we'll do
const
handle close snack
this will be a function
and we'll just say
set show erc20 approval status to false
and then set
show stake
token
i'm just going to copy paste it
this one also to false awesome now if we
go back we refresh our front ends here
looks like i forgot to do an on close
ah okay yep
we'll do handle on closed snack here
for the alerts as well
and there are no
tags there there are no brackets there
so i've got to change that
but now if we go to our front end we'll
do a quick refresh we see everything in
here looking great
let's add one in here we'll hit stake
this will pop up we'll confirm we'll get
the little progress bar which is exactly
what we want and you see here now we get
this little pop-up it says erc20 token
transfer approved now approve the second
transaction this should
uh go away after a few seconds or not
let's just approve this second one oh
looks like it now went away so maybe it
was a little bit longer than five
seconds
and now we can see the token stake
popped up perfect
so we have some pop-ups we have a little
bit of ways to show the user how to do
everything
now you'll notice this doesn't look
exactly like what we see in the github
repo right and this github repo looks a
little bit different it's got this
little slidey bar it's got this second
token farm contract for unstaking
however a lot of what we're going to
keep doing is just going to be a lot of
more front-end stuff and at this point
you pretty much should have everything
that you need to build the rest of the
contract
so what we're going to do
is we're going to have the rest of this
be a challenge if you want if you would
like to complete it you can absolutely
add this second tokenfarb contract with
this unstake all weth bit or unstay golf
fau dap etc
we're going to have two versions
of this front end in here we're going to
have kind of this more cleaned up
version and then we're going to have a
little bit more raw version this one's
the the more raw version all the code is
going to be there so if you want to say
i don't really want to code and follow
this along you can just copy paste the
code or you can say you know what i'm
going to do
this unstaking part all myself and that
will be awesome also fantastic you
should be incredibly proud of yourself
because at the end of the day at this
point you have a way to stake
tokens into a smart contract and build a
front end which is absolutely massive
absolutely fantastic you should be
patting yourself in the back excellent
job excellent job let's go ahead and
wrap this course up welcome back friends
how do you feel good
smarter empowered ready to take on the
world
excellent well you absolutely 100 should
be and you deserve a massive round of
applause because you have just done
something fantastic you have started
your journey and equipped yourself with
the tools to become an incredibly
powerful intelligent smart contract
engineer in the space now i would be
remiss if i didn't comment on security
and audits when it comes to doing your
smart contracts as you know all these
smart contracts are available on chain
for anybody to see and anybody to work
with this means that having a security
mindset is incredibly incredibly
important and i highly recommend if
you're going to go maintenance if you're
going to take your application onto a
real network where it's going to be
securing a lot of people's money and a
lot of people's assets you absolutely
need to get an audit there is no excuse
for not getting an audit and having an
application that's securing a lot of
people's money getting an audit is
essentially just having somebody else
peer review your code looking for any
vulnerabilities that could be exploited
an audit can be the difference between
your protocol
skyrocketing into the future and doing
fantastically successfully
or dwindling getting hacked and everyone
losing faith in your abilities audits
are essential we've got some helpful
links in the github repository
associated with this course to learn
more about audits who to get them from
and some helpful tips on setting your
smart contracts up to make auditors
lives easier while we're talking about
security it's also helpful to know some
of the most common attacks in this space
we've got another wonderful link in the
github repository that will show you
some of these attacks and how to get
around them and what they actually look
like two of them that are big enough
that i think i need to mention here are
going to be oracle attacks and
re-entrancy attacks these are the two
attacks that i see happen most often
unfortunately right now in the state of
d5 protocols get hacked for millions of
dollars literally almost every day and
it is a travesty to the space that this
is happening most of the time these
attacks are preventable so understanding
some of these security tips doing your
due diligence and getting an audit is
going to make both you as a smart
contract developer and as adapt
developer and as a protocol better but
also the entire space is going to be
more safe secure and easier for
newcomers to get into thankfully you can
sleep a lot easier on those oracle
manipulation attacks because you've
learned some best practices for working
with oracle's you've learned how to work
with a chain-link decentralized oracle
network to get your data and do your
external computation using a chain-link
decentralized oracle network or a dawn
will solve these oracle manipulation
attacks so that you don't have to deal
with people manipulating a centralized
oracle because you are going to be using
a decentralized one reentrancy attacks
are a little bit trickier to detect but
whenever you call an external smart
contract a smart contract outside your
project you especially should think hm
does somebody in that smart contract
have access to changing some variables
that i don't want them to change again
we have some wonderful examples in that
github repository associated with this
course to teach you more about that
additionally i highly recommend
everybody check out both ethernet and
damn vulnerable defy these are two games
that show you some of the exploits and
some of the low-level solidity things
you can do that you might want to look
out for when you're writing your smart
contracts all right so now that we've
got the security piece out of the way
once again huge congratulations for
getting this far you now have the tools
to build a better world to build these
smart contract applications and to
empower yourself and your community with
these blockchain applications now the
first question you might be asking is
patrick this is great but
where do i go now what do i do i have
all these tools i want to go use them
absolutely my first bit of advice here
is going to say you can always learn
more and there's always going to be more
places to learn and grow and even though
this course gave you a full setup of
everything that you're going to need to
get going and get off the races and
start building it's good to know where
else you can learn more and where else
you can grow some amazing places are
going to be crypto zombies dapp
university ivan on tech chain shop eat
the blocks patrick collins my youtube
channel austin griffith's youtube
channel nader's youtube channel the
ethereum.org website
chain link blogs and really any other
material you can get your hands on while
you're learning you should 100 be
growing with the community this is
something that i've been pushing from
the start
blockchain and smart contract world is
different from these corporate worlds we
are a decentralized open source group
open source open source ecosystem where
we flourish if the people around us
flourish so growing and connecting with
the community is a absolute must and is
eight and it's a way to really
accelerate all the momentum that you're
getting after taking this course twitter
the reddit brownie discord the ethereum
discord the chain link discord there are
all these discords in all these
communities that you can jump in you can
grow ask questions chat spread ideas
then once you're in these communities
then you can start really coding and
tinkering more hackathons are some of
the best places to put your stuff to the
test and also really learn and build and
grow in the blockchain space there are
hackathons happening all the time and
these are places where you can show up
you can learn from some of the sponsors
you can build really cool things and you
can win prizes as well we've seen some
projects win a hackathon go on to raise
millions in seed funding and become a
billion dollar protocol some have gotten
advisors from top investors like mark
cuban and these products do wildly
successful but at the same time we also
see a huge uptick in a huge number of
the newcomers in this space people have
never written a smart contract never
written any of the code come in try
learn grow and come out an incredibly
powerful engineer with more networking
and with more people around them who
they know they can lean on and talk to
in this community so whether or not you
want to win a hackbond doesn't really
matter hackathons are a great place to
sharpen your coding skills get better
meet some people maybe win some prizes
and a lot of these decentralized
products do look at the hackathon
winners looking for some talent to pick
up for their teams a lot of the
engineers that i work with right now i
work with them because they got picked
up from a hackathon so hackathons are
great places to go eat global eath india
eath global eth india and the chain like
hackathon are some of the best
hackathons in the business so be sure to
check those out all these decentralized
protocols have a ton of work that people
can be doing to help grow their protocol
in some way and they all have community
grant projects where people can come in
propose some grant propose something to
the community and that person builds it
out so if you have an idea on how to
improve one of these decentralized
applications you can go ahead propose
what you want to improve and if you get
approved you could be awarded a grant to
work on that as well you can become a
smart contract consultant here you can
start offering your services to people
who are looking for really strong
solidity and smart contract developers
you can start reaching out to some of
these projects now that you have these
skills you can start reaching out to
other people saying hey i've got a great
idea of something i want to build and
i'm looking to take it to the next level
and that's the most important piece of
advice i have for you here
just
build just have a good time and build
things that you enjoy building you'll
learn the most the fastest by building
tinkering and trying new things and this
is also one of the best ways to meet
people in the industry everybody that i
work with in my life in this space i
work with them because i was building
something and we became close because we
were working on the same things i feel
incredibly lucky to have met and
interact with so many fantastic people
in this space and i hope that one day
i'll get to meet and interact with you
too so good luck to you all and let's
rebuild this world let's make a world
where there's more economic opportunity
there's more equality and let's rebuild
some of this institutional trust while
having an absolute blast in this wild
west that is cryptocurrency smart
contracts and blockchain like i said i
hope to meet you all one day and just do
me a favor and make today an amazing day
take care everybody
