<template>
    <div class="columns is-multiline">
        <div class="column is-one-third">
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/pie"/>
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/polar"/>
        </div>
        <div class="column is-one-third">
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/bar"/>
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/bubble"/>
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/line"/>
        </div>
        <div class="column is-one-third">
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/radar"/>
            <chart-card class="is-rounded raises-on-hover mb-3"
                source="/api/dashboard/doughnut"/>
        </div>
    </div>
</template>

<script>

import { EnsoChartCard as ChartCard } from '@enso-ui/charts/bulma';

export default {
    name: 'Index',

    components: { ChartCard },
};

</script>
