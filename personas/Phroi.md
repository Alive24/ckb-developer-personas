# Phroi

## 🧑‍💻 **About**

> Can provide at any level of details you feel comfortable with.

- **Location**: South East Asia until the end of August, then Europe.
- **Timezone**: +7 until the end of August, then +1.
- **GitHub**: [@Phroi](https://github.com/Phroi)
- **Telegram**: [@Phroi](https://t.me/Phroi), feel free to reach on [Nervos Nation](https://t.me/NervosNation/307406)
- **Nervos Talk**: [@Phroi](https://talk.nervos.org/u/phroi/)

### **🛠️ Skills & Stacks**

- English
- Rust & TypeScript
- CKB L1 Scripts & dApps

### 🧠 **Awareness**

> how much do you know about Dev Rel?

At least once month I pick DevRels brains and I'm pretty happy.

---

### 💼 **Business**

> your role/organization when you build?

- Built my first DApp iCKB: design, L1 Script coding and DApp.
- I share the issues I encountered building iCKB and try to learn from them.
- I try to provide fast feedback on DevRel developments, like SSRI and CCC.

---

### 🚀 **Personal Development**

> how and where did you learn about CKB?

I joined with a team the August 2021 Nervos Hackathon: Broaden the Spectrum, in occasion of Godwoken launch. We placed third among peers. Later on we continued working on the Hackathon idea until May 2022, when I left for becoming a solo Indie Hacker.

During February 2022, while testing the ground for a NervosDAO based ISPO, I discovered the untapped need for a token that liquefies and bridges interests from L1 to L2 and so I started researching its feasibility. Little by little this idea morphed into iCKB.

---

### 🤝 **Community**

> Places where you're most active in relation to CKB

- Telegram:
  - Nervos Nation
  - SSRI & BEYOND
- Nervos Talk
- Discord: Nervos Network

---

### ⚡ **Pain Points**

> - what pain points do you plan to solve by building in CKB
> - (what issues do you still often encounter when building in CKB)

While developing iCKB I encountered quite a bit of roadblocks, most around lacking documentation. I'd say that most of this documentation issues have been addressed, especially thanks to CKB DevRel Team and CCC development.

Still there are [technical issues](https://github.com/ickb/whitepaper/issues) that could be better addressed:

1. [Output locks do not validate](https://talk.nervos.org/t/nip-allow-some-output-lock-scripts-to-validate/8636). While this can be worked around, it creates unnecessary development friction and cell forgery that is [impossible to prevent](https://github.com/ickb/whitepaper/issues/19). [Jan proposed two cool higher level solution](https://github.com/ickb/whitepaper/issues/19#issuecomment-2647172045) that I'd like to explore more in the future with the CKB DevRel team.

2. Using non-signature-based locks in conjunction with `sighash_all`-based locks creates issues of [witness malleability](https://github.com/ickb/whitepaper/issues/22). The recently proposed [CKB_TX_MESSAGE_ALL](https://github.com/nervosnetwork/rfcs/pull/446) addresses other problems, but it doesn't seem to address this one in particular.

---

### 💡 **Use Cases**

> what can/did you do/build with CKB?

iCKB

---

### 🛠️ **Products**

> What CKB related products do you use

#### Current

- ckb-std
- CCC

#### Future

- ckb-ssri-std
- fiber
- rgbpp, possibly

---

## Developer Journey Mapping

### Discover

> how did you discover CKB?

Hackathon

### Evaluate

> what made you want to build in CKB?

- Creating iCKB from zero knowledge of Nervos L1, a good challenge!! 💪😁
- Nervos L1 cell model has quite a bit of constraints, but it feels quite a bit safer that Solidity.

### Learn

> how and where did you learn your skills to build in CKB?

Reading the docs, asking a lot of questions and experimenting.

### Build

> how do you usually build in CKB?

- Ideation, nowadays this process is explored with the help of AI.
- Model iteration, understanding how to implement the idea while fitting withing constraints imposed by Cell model.
- Model examination from adversarial perspective (How can the model be hacked?)
- Proof of concept
- Iteration until satisfied with the result

### Scale

> how do you decide what to build?

- Solutions to Community problems that are interesting to work on.
- Needs expressed by Foundation and Community.
