<template>
    <DocSectionText v-bind="$attrs"> </DocSectionText>
    <div class="card">
        <Fieldset legend="Header" :toggleable="true" :pt="{ legend: { class: 'bg-primary' }, legendTitle: { class: 'text-white' }, togglerIcon: { class: 'text-white' } }">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </p>
        </Fieldset>
    </div>
    <DocSectionCode :code="code" />
</template>

<script>
export default {
    data() {
        return {
            code: {
                basic: `
<Fieldset
    legend="Header"
    :toggleable="true"
    :pt="{
        legend: { class: 'bg-primary' },
        legendTitle: { class: 'text-white' },
        togglerIcon: { class: 'text-white' }
    }">
    <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
</Fieldset>
`,
                options: `
<template>
    <div class="card">
        <Fieldset
            legend="Header"
            :toggleable="true"
            :pt="{
                legend: { class: 'bg-primary' },
                legendTitle: { class: 'text-white' },
                togglerIcon: { class: 'text-white' }
            }">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </p>
        </Fieldset>
    </div>
</template>
`,
                composition: `
<template>
    <div class="card">
        <Fieldset
            legend="Header"
            :toggleable="true"
            :pt="{
                legend: { class: 'bg-primary' },
                legendTitle: { class: 'text-white' },
                togglerIcon: { class: 'text-white' }
            }">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </p>
        </Fieldset>
    </div>
</template>`
            }
        };
    }
};
</script>
