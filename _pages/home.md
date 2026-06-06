---
layout: default2
permalink: /
title: Decoupled Intelligence @ NeurIPS 2026
nav_order: 1
---

<!--  <div class="button-container"> -->
<!--      <a href="https://forms.office.com/e/HK2YV14gSi" class="custom-button">Register for Workshop</a> -->
<!--  <a href="https://forms.office.com/e/LDj3QMiAYZ" class="custom-button">Give a talk and/or present poster of your work</a> -->
<!--  </div> -->

<!-- <br> -->

### Workshop Description

Foundation models (FMs) have been driving recent progress in AI, but at the same time, they reinforce a monolithic view of intelligence: more capabilities through larger models trained on vast datasets. Systems based on monolithic foundation models often fail under distribution shifts across domains, tasks, or local constraints. Inappropriate hidden priors and static internalized knowledge are carried into new inferences, leading to poor generalization, unreliable conclusions, and safety issues, as illustrated by reported failures involving [hallucinated personal claims](https://www.bbc.com/news/articles/c0kgydkr516o) and AI assistant errors in news summaries. On the other hand, alternative paradigms of intelligence built on decoupling and externalization are emerging: decoupling intention from intelligence (e.g., Scientist AI), knowledge from reasoning, identity from usage (e.g., Open Anonymity's "VPN for AI inference"), short-term updatable memory from long-term parametric memory (e.g., LMLM, RAG, tool use, and memory modules), and local data from global representations (e.g., federated learning).

In 2026, AI systems are also facing mounting pressures from data ownership issues such as copyright disputes, licensing restrictions, privacy regulation, and data scarcity, while at the same time needing to handle value misalignment issues, with some groups demanding models that provide answers closer to their values. These constraints make decoupled AI architectures that respect user sovereignty and values not only desirable, but necessary. In industry, the emerging trend that foundation models do not constitute a full product of their own, and that they should instead be developed for compatibility with user-controlled memory modules, application-specific harnesses (e.g., [AI harness engineering](https://openreview.net/forum?id=3hXEPbG0dh) and [code as agent harness](https://arxiv.org/abs/2605.18747)), and other agentic orchestration layers, seems to offer a promising path toward more flexible and modular systems. This approach allows users to retain control over their data and workflows while reducing dependence on any single provider or its designated values, thereby mitigating the risks of lock-in to particular providers.

Beyond an AI system challenge, decoupling raises a fundamental question: what is the irreducible core of intelligence, and what can be separated from it? As memory, knowledge, intention, identity, and computation become externalized, understanding whether decoupling can enable a more adaptive and reliable form of intelligence than monolithic foundation models becomes a central scientific and philosophical inquiry. The rise of multimodal foundation models further sharpens these questions. While decoupling has shown promise in language-centric systems, it remains unclear how reasoning, memory, and knowledge should be separated when intelligence operates over jointly encoded visual, auditory, textual, and sensor modalities. Understanding which components should remain shared and which should be modularized is becoming a central scientific challenge.

Taken together, both emerging scientific directions and growing societal demands point towards decoupled AI systems as increasingly important alternatives to monolithic foundation models. This workshop therefore calls for a different trajectory of decoupled intelligence. By convening researchers across machine learning, systems, and governance, this workshop aims to develop shared taxonomies, evaluation frameworks, and architectural principles for decoupled AI systems that are inherently adaptable under changing data and diverse deployment constraints, including different cultural values, and therefore by design support better efficiency, safety, and user sovereignty.

<br>

### Importance, Novelty, and Audience

As a field, we have seen major progress in AI in recent years through the monolithic foundation model paradigm. However, as the initial excitement around "FM = AGI" gradually fades, we are facing a possible redefinition of future intelligence itself. Decoupling is about creating and maintaining meaningful boundaries: separating partial intelligence from static model parameters, and deciding what systems should retain internally versus what they should externalize. This challenge spans multiple areas:

- In **efficiency research**, systems must determine which components to reuse and which to replace.

- In **safety-critical applications**, systems must preserve abstract reasoning capabilities without leaking domain-specific assumptions across contexts.

- In **privacy-sensitive applications**, systems must determine what should remain in centralized parameters versus local or user-controlled storage. Decoupling creates a boundary between shared model capabilities and user-private data.

- In **multimodal foundation models**, systems must separate shared abstract representations and operations in latent space from modality-specific knowledge.

- In **continual learning**, systems must distinguish between useful memory retention and harmful rigidity.

However, there is still a lack of common language to facilitate scientific discussion in decoupling. Nor do we have standardized benchmarks and evaluations of whether decoupling is successful, or whether different levels of decoupling are needed for different scenarios. All of these are unaddressed community needs. In this workshop, we expect audiences across the above areas to come together, sharpen the common thread of decoupling, develop a common taxonomy for deepening this line of research, and pave the way for future AI systems that go beyond foundation models.

### [Call for Papers]({{ '/call/' | relative_url }}) and [Competition]({{ '/competition/' | relative_url }})

Our workshop will comprise a standard CFP process and a competition to engage different audiences. In our tentative schedule, we have six invited talks, two contributed-talk sessions, two poster sessions, one panel discussion, and dedicated sessions for the competition overview and winner talks. The panel discussion and extended poster sessions are designed to support substantive discussion.


<br>

### :sparkles: Keynote Speakers

<html>
    <div class="team-container speaker-container">
        <div class="sponsor">
            <img src="{{ '/assets/img/speakers/yoshua_bengio.jpg' | relative_url }}" alt="Yoshua Bengio">
            <p><a href="https://yoshuabengio.org/">Yoshua Bengio</a>
            <br>Mila <br> Universit&eacute; de Montr&eacute;al<br>Talk at TBD</p>
        </div>
        <div class="sponsor">
            <img src="{{ '/assets/img/speakers/karl_friston.jpg' | relative_url }}" alt="Karl Friston">
            <p><a href="https://profiles.ucl.ac.uk/2747-karl-friston">Karl Friston</a>
            <br>University College London<br>Talk at TBD</p>
        </div>
        <div class="sponsor">
            <img src="{{ '/assets/img/speakers/jakob_hohwy.jpg' | relative_url }}" alt="Jakob Hohwy">
            <p><a href="https://research.monash.edu/en/persons/jakob-hohwy/">Jakob Hohwy</a>
            <br>Monash University<br>Talk at TBD</p>
        </div>
        <div class="sponsor">
            <img src="{{ '/assets/img/speakers/percy_liang.jpg' | relative_url }}" alt="Percy Liang">
            <p><a href="https://cs.stanford.edu/~pliang/">Percy Liang</a>
            <br>Stanford University<br>Talk at TBD</p>
        </div>
        <div class="sponsor">
            <img src="{{ '/assets/img/speakers/jennifer_sun.jpg' | relative_url }}" alt="Jennifer Sun">
            <p><a href="https://jenjsun.com/">Jennifer Sun</a>
            <br>Cornell University<br>Talk at TBD</p>
        </div>
        <div class="sponsor">
            <img src="{{ '/assets/img/speakers/philip_isola.jpg' | relative_url }}" alt="Philip Isola">
            <p><a href="https://web.mit.edu/phillipi/">Philip Isola</a>
            <br>MIT<br>Talk at TBD</p>
        </div>
    </div>
</html>


<!-- ## Organization Chairs -->
<!-- <html> -->
<!--     <div class="team-container"> -->
<!--         <div class="team-member">
<!--             <img src="/assets/img/organizers/luo_mai.jpg" alt="Name 7"> -->
<!--             <p><a href="https://luomai.github.io/">Luo Mai</a> -->
<!--             <br>University of Edinburgh</p> -->
<!--         </div> -->
<!--         <div class="team-member"> -->
<!--             <img src="/assets/img/organizers/edoardo_ponti.jpg" alt="Name 8"> -->
<!--             <p><a href="https://ducdauge.github.io/">Edoardo Ponti</a> -->
<!--             <br>University of Edinburgh</p> -->
<!--         </div> -->
<!--     </div> --> 
<!-- </html> -->

<br>

### Organizers

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/yihong_chen.jpg' | relative_url }}" alt="Yihong Chen">
            <p><a href="https://oatml.cs.ox.ac.uk/members/yihong_chen/">Yihong Chen</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/yi_joshua_ren.jpg' | relative_url }}" alt="Yi Joshua Ren">
            <p><a href="https://oatml.cs.ox.ac.uk/members/yi_ren/">Yi (Joshua) Ren</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/yarin_gal.jpg' | relative_url }}" alt="Yarin Gal">
            <p><a href="https://oatml.cs.ox.ac.uk/members/yarin/">Yarin Gal</a>
            <br>University of Oxford <br> AISI</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/pierre_luc_st_charles.jpg' | relative_url }}" alt="Pierre-Luc St-Charles">
            <p><a href="https://www.linkedin.com/in/plstcharles/">Pierre-Luc St-Charles</a>
            <br>LawZero</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/gael_gendron.jpg' | relative_url }}" alt="Gael Gendron">
            <p><a href="https://ggendro.github.io/">Gaël Gendron</a>
            <br>LawZero</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/kevin_kasa.jpg' | relative_url }}" alt="Kevin Kasa">
            <p><a href="https://kevinkasa.github.io/">Kevin Kasa</a>
            <br>LawZero</p>
        </div>
        <div class="team-member">
            <img src="{{ '/assets/img/organizers/sebastien_bratieres.jpg' | relative_url }}" alt="Sebastien Bratieres">
            <p><a href="https://it.linkedin.com/in/sebastien-bratieres">Sébastien Bratières</a>
            <br>Translated <br> DVPS</p>
        </div>
    </div>
</html>

<!--
### Scientific Committee

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/olivier_pietquin.jpg" alt="Name 9">
            <p><a href="https://www.linkedin.com/in/opietquin/">Olivier Pietquin</a>
            <br>Cohere</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/kenny_smith.jpeg" alt="Name 9">
            <p><a href="http://www.lel.ed.ac.uk/~kenny/">Kenny Smith</a>
            <br>University of Edinburgh</p>
        </div>
    </div>
</html>
-->

<br>

### Sponsors

<html>
    <div class="sponsors-container">
        <a class="sponsor-logo" href="https://www.ox.ac.uk/" aria-label="University of Oxford">
            <img src="{{ '/assets/img/sponsors/oxford.png' | relative_url }}" alt="University of Oxford">
        </a>
        <a class="sponsor-logo" href="https://lawzero.org/" aria-label="LawZero">
            <img src="{{ '/assets/img/sponsors/lawzero.png' | relative_url }}" alt="LawZero">
        </a>
        <a class="sponsor-logo" href="https://www.translated.com/research" aria-label="DVPS">
            <img src="{{ '/assets/img/sponsors/dvps.png' | relative_url }}" alt="DVPS">
        </a>
    </div>
</html>

<style>
.button-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 16px;
    margin: 24px 0;
    flex-wrap: wrap;
}

.custom-button {
    background-color: var(--global-theme-color);
    border: none;
    color: white;
    padding: 12px 24px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    cursor: pointer;
    border-radius: 6px;
}

.team-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 28px 24px;
    max-width: 1024px;
    padding: 18px 0 28px;
    margin: 0 auto;
}

.speaker-container {
    grid-template-columns: repeat(3, minmax(0, 1fr));
}

.team-member,
.sponsor {
    text-align: center;
    min-width: 0;
}

.team-member img {
    object-fit: cover;
    border: 4px solid rgba(0, 118, 223, 0.12);
    border-radius: 50%;
    box-shadow: 0 10px 24px rgba(0, 61, 115, 0.1);
    height: 180px;
    margin-bottom: 12px;
    width: 180px;
}

.team-member p,
.sponsor p {
    line-height: 1.45;
    margin: 0;
}

.team-member p a,
.sponsor p a {
    color: var(--global-theme-color);
    display: inline-block;
    font-size: 18px;
    font-weight: bold;
    text-decoration: none;
}

.team-member p a:hover,
.sponsor p a:hover {
    text-decoration: underline;
}

.sponsor {
    font-size: 18px;
    font-weight: bold;
}

.sponsor img {
    aspect-ratio: 1 / 1;
    border-radius: 6px;
    box-shadow: 0 12px 28px rgba(0, 61, 115, 0.12);
    margin-bottom: 12px;
    object-fit: cover;
    width: 100%;
}

.sponsors-container {
    align-items: center;
    display: grid;
    gap: 28px;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    margin: 18px auto 36px;
    max-width: 860px;
}

.sponsor-logo {
    align-items: center;
    border-radius: 6px;
    display: flex;
    justify-content: center;
    min-height: 96px;
    padding: 18px 22px;
}

.sponsor-logo img {
    max-height: 88px;
    max-width: 100%;
    object-fit: contain;
}

.caption {
    margin-top: 12px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
}

.right-half {
    flex: 1;
    height: 500px;
}

.news-box {
    border: 1px solid rgba(0, 118, 223, 0.16);
    padding: 16px;
    max-width: 680px;
    margin: 0 auto;
    background-color: rgba(0, 118, 223, 0.04);
}

@media (max-width: 768px) {
    .speaker-container {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

@media (max-width: 600px) {
    .news-box {
        width: 100%;
    }

    .team-container {
        grid-template-columns: 1fr;
    }

    .speaker-container {
        grid-template-columns: 1fr;
    }

    .team-member img {
        height: 160px;
        width: 160px;
    }

    .sponsors-container {
        grid-template-columns: 1fr;
    }
}
</style>

<br><br>
