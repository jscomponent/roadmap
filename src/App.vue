<template>
    <div>
        <h2 style="font-family:'Kolker Brush', cursive;font-size:80px;margin-bottom:20px;color:#404040ff;box-sizing:border-box;display:block;margin-top:80px">
            Roadmap
        </h2>
        <div style="width:25px;margin-right:auto;margin-left:auto;background-color:#242424ff;border-top-left-radius:8px;border-top-right-radius:8px;border-bottom-left-radius:4px;border-bottom-right-radius:4px;padding-top:10px;padding-bottom:160px;z-index:1;position:relative">
            <div class="card" style="background-color:#6cd99bff">
                <time datetime="">
                    {{
                        new Date('2023-02-25')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    comp prev img
                </p>
            </div>
            <div class="card" style="background-color:#424242ff;color:#fafafaff">
                <time datetime="">
                    {{
                        new Date('2023-02-26')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Keyframe timeline
                </p>
            </div>
            <div class="card">
                <time datetime="">
                    {{
                        new Date('2023-03-12')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Landing page
                </p>
            </div>
            <div class="card">
                <time datetime="">
                    {{
                        new Date('2023-03-19')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Free & paid version
                </p>
            </div>
            <div class="card">
                <time datetime="">
                    {{
                        new Date('2023-03-26')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Documentation page
                </p>
            </div>
            <div class="card" style="background-color:#72c0f7ff">
                <time datetime="">
                    {{
                        new Date('2023-04-02')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <header>
                    Anitas bursdag ❤️
                </header>
                <p>
                    Beta announcement
                </p>
            </div>
            <div class="card">
                <time datetime="">
                    {{
                        new Date('2023-05-01')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Demo components & bugfix
                </p>
            </div>
            <div class="card" style="background-color:#e4e6a5ff">
                <time datetime="">
                    {{
                        new Date('2023-06-01')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Stable release
                </p>
            </div>
            <div class="card" style="background-color:#e4e6a5ff">
                <time datetime="">
                    {{
                        new Date('2023-06-01')
                        .toLocaleDateString([], {
                        year: 'numeric',
                        month: '2-digit',
                        day: '2-digit'
                        })
                    }}
                </time>
                <p>
                    Stable release
                </p>
            </div>
        </div>
        <div style="width:100%;z-index:0;margin-top:-40px;height:140px;position:relative;background:radial-gradient(circle, rgba(174,201,102,1) 0%, rgba(126,173,62,1) 100%);border-top-width:1px;border-color:#d7fa91ff;border-style:solid;border-bottom-width:0px;border-right-width:0px;border-left-width:0px">
            <div style="position:absolute;width:100%;bottom:-200px;top:100%;background:linear-gradient(353deg, rgba(88,88,88,1) 0%, rgba(56,56,56,1) 100%);text-align:center;color:#f5f5f5ff;padding-top:100px">
                <img src="@/assets/jsComponent.png" style="width:335;height:auto;margin-bottom:40px;margin-left:35px;box-sizing:border-box;display:inline-block;position:relative;margin-top:-60px" /> <span style="display:block;margin-bottom:35px">
                    © Siglar Development AS
                    - All rights reserved
                    {{new Date().getFullYear()}}
                </span>
            </div>
        </div>
    </div>
</template>
<script>
    export default {};
</script>
<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800;900&display=swap');

    @import url('https://fonts.googleapis.com/css2?family=Kolker+Brush&display=swap');

    .card:nth-child(2n) {
        margin-left: -141px;
        border-top-left-radius: 8px;
        border-bottom-left-radius: 8px;
        border-right-width: 0px;
    }

    @charset UTF-8;

    @charset UTF-8;

    @font-face {
        font-family: font-family;
        src: verdana;
    }

    @keyframes test {
        30% {}

        from {}

        to {}
    }

    @keyframes testing {
        30% {}

        from {}

        to {}
    }

    .card:nth-child(2n-1) {
        margin-left: 100%;
        border-top-right-radius: 8px;
        border-bottom-right-radius: 8px;
        border-left-width: 0px;
    }

    .card {
        width: 140px;
        background-color: #b5ad9aff;
        padding-top: 20px;
        padding-bottom: 10px;
        color: #242424ff;
        border-style: double;
    }

    .card time {
        font-size: 13px;
        font-weight: 689;
    }

    .card:nth-child(2n-1) {
        margin-left: 100%;
        border-top-right-radius: 8px;
        border-bottom-right-radius: 8px;
        border-left-width: 0px;
    }
</style>
<style>
    .card p {
        padding-right: 10px;
        padding-left: 10px;
        font-size: 12px;
        margin-top: 7px;
    }

    body,
    html,
    #app {
        margin-left: 0px;
        margin-bottom: 0px;
        margin-right: 0px;
        font-family: 'Montserrat', sans-serif;
        background: radial-gradient(circle, rgba(240, 242, 185, 1) 0%, rgba(112, 204, 235, 1) 100%);
    }

    div {
        text-align: center;
    }
</style>