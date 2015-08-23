# Implementation

That's where all the fun (or rather routine) begins! In fact, you could just do some chaotic coding until you get satisfying results, but I usually prefer to do some self-management magic here. Once again, it's absolutely up to you: some people are just not into this sort of thing; I guarantee that it will increase your productivity though.

### Structuring the workflow
I usually outline all the major features (usually, up to five) and split them up into a bunch of "tasks", by possible struggles and potential complications. This will save your focus on things that matter **now** and keep the workflow structured. No need to anyhow document this in the project sources, just use a pen and some random piece of paper. Oh, love it! I write stuff down with Staedtler's *Pigment Liner 0.5* pen (it's like $4 each) and any kind of thick paper (so much cooler to write on!). It's absolutely worth it.

### Be realistic
Estimate your own strength and efforts carefully! I wrote this in bold since it's a common pitfall, people (and I am not an exception) keep on facing from time to time... You want to get things finished and it's critical to correctly evaluate your own skills. It might be sophisticated at first, but as times goes on, you'd become more experienced and realistic. You should focus on little things and do them well (aka *Unix-way*). Once again, it's all about changing the context: building a huge application, for instance, Gmail requires some time and effort and you most surely won't be able to do that on your own: as time goes on, you won't be enthusiastic enough to keep on going.

### Scheduling
Planning is yet another great trick and in fact, obligatory technique in commerical software engineering. Basically, it's all about locking a desired product state to some calendar date (aka *Milestones*). Here are some common early versioning labels, you'd might want to use for your projects:

1. **PoC** (Proof of Concept) is an implementation of a certain idea to demonstrate its feasibility. Usually it's nothing but some algorithm (for Google it could be PageRank) or interaction (for Facebook it could be Messaging), nothing more.
2. **MVP** (Minimum Viable Product) is the product with the highest return on investment versus risk. Basically, some fairly working prototype with highly limited list of features, cooked in a week or two.
3. **Alpha** version matches an buggy and pretty unstable, but pretty accomplished product. Alpha is usually the first version of the product shown to wider audience, testing-feedback-fixing.
4. **Beta** version matches an unpolished yet complete product with all the key features implemented already. Usually, beta versions are public and quite often, free to use. Some teams tend to put the "feature freeze", which means "no more features, solving bugs only" on this stage.
5. **RC** (Release Candidate) is a thin layer between Beta and Release: definitely no more features, fixing known bugs, solving performance and stability issues and polishing UX (user experience).

There we go, release time! At this point you'd most likely switch to [semantic versioning](http://semver.org/) labels in format of `<major>.<minor>.<patch>` with patch being intermediate. Here are a few examples: `1.0`, `1.0.12`, `1.7`. Major versions are usually taged on really significant changes. Minor and patch changes reflect stable features and minor software fixes and mustn't brake existing compatibility. Do your best to not piss people off and read the link above carefully, please.
