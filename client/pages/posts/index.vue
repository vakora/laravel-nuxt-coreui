<template>
    <card :title="$t('posts')" >
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem ipsum, iure nisi pariatur provident repudiandae ullam. Consequuntur, laudantium quo. Adipisci aliquam amet at culpa ea ipsam magnam officia similique ut!</p>
        <VButton :large="true">sad</VButton>
    </card>
</template>

<script>
    export default {
        data: () => ({

        }),
        layout: 'default',
        head () {
            return { title: this.$t('home') }
        },
        middleware: 'auth' ,
    }
</script>
