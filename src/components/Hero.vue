<template>
    <section class="hero is-medium has-text-centered">
        <div class="hero-body">
            <div class="container">
                <h1 class="title is-1 has-text-primary">{{title}}</h1>
                <div>
                    <h2 class="subtitle"><span class="has-text-primary is-italic">return </span><span class="has-text-white">$this</span>-><span>{{branch}}()</span>;</h2>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    props: [
        'title',
        'branch',
    ]
}
</script>