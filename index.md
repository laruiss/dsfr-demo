---
home: true
tagline: Tagline
heroText: Hero text
actionText: Commencer
actionLink: /guide/
features:
  - title: Documentation complète
    details: Tous les composants sont documentés avec tous leurs variants
  - title: Démo des composants 
    details: Tous les composants sont visibles, avec le code associés et tous leurs variants
---

<script setup>
import {onMounted} from 'vue'
import '@gouvfr/dsfr/dist/dsfr/dsfr.min.css'

import DsfrButton from './composants/DsfrButton.vue'
import DsfrAccordion from './composants/DsfrAccordion.vue'
import DsfrBreadcrumb from './composants/DsfrBreadcrumb.vue'

onMounted(() => import('@gouvfr/dsfr/dist/dsfr/dsfr.module.js'))
</script>

# Comment commencer

<DsfrAccordion />
<DsfrBreadcrumb />

<<< @/composants/dsfr-breadcrumb-template-1.html
