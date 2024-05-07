<script setup>
import ResumeItem from './ResumeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
</script>

<template>
  <ResumeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>University of Nebraska-Lincoln</template>
    <h3>BSBA in Economics (with Highest Distinction)</h3>
    <h3>BA in Mathematics (with High Distinction)</h3>
    <h3>Phi Beta Kappa</h3>
  </ResumeItem>

  <ResumeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Quantitative Strategist II at Buildertrend</template>
    <p>
      Supported Buildertrend's initiative to adopt a data-centric decision making framework by,
      e.g., creating educational materials to reorient the analytics department around CI/CD design
      principles (part of a department-wide strategic shift toward quality and trust assurance).
    </p>
    <br />
    <p>
      Identified areas for improvement on BT's Tableau server by purpose-building admin tools to
      identify and address inefficiencies. Eliminated key redundancies and refactored
      resource-intensive assets, resulting in more than a 50% reduction in server runtime.
    </p>
    <br />
    <p>
      Conceived, developed, and delivered a two-day lecture series on Tableau best practices for the
      Data Science team, culminating in a pair programming exercise demonstrating the new standards,
      which have since been widely adopted by the organization -- including in the training of new
      Tableau users.
    </p>
  </ResumeItem>

  <ResumeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Bureau of Business Research</template>
    <p>
      Advanced a research project relating to the migration implications of a given state's adoption
      of -- or failure to adopt -- an income tax exemption for military pensioners' retirement pay
      (particularly when a state's neighbors differ in their tax treatment of this form of income).
    </p>
    <br />
    <p>
      Assessed the effect of the Nebraska Historic Tax Credit renovation incentive program on
      property values of treated properties and of surrounding areas, with a focus on the Lincoln
      and Omaha, NE metro areas.
    </p>
  </ResumeItem>
  <ResumeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Personal Interests</template>
    Interests include gardening, dreampop music, long walks, DIY electronics, and train travel --
    among many other things.
  </ResumeItem>
</template>
