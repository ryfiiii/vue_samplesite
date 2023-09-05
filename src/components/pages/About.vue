<template>
    <div id="about">
        <div class="glass-card">
            <div class="motto">
                <h1>モットー</h1>
                <p>~お客様の大切は私たちの大切~</p>
            </div>
            <div class="company">
                <h1>会社概要</h1>
                <table>
                    <tr>
                        <th>社名</th>
                        <td>サンプル株式会社</td>
                    </tr>
                    <tr>
                        <th>役員</th>
                        <td>代表取締役社長: 山田 太郎 <br>代表取締役会長: 加藤 健太<br>取締役: 鈴木 花子</td>
                    </tr>
                    <tr>
                        <th>職員数</th>
                        <td>300名</td>
                    </tr>
                    <tr>
                        <th>住所</th>
                        <td>大阪府大阪市北区梅田1-1-1</td>
                    </tr>
                </table>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "About",
}
</script>

<style scoped>
/*==== About ==== */
#about {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100vh;
}

.glass-card {
    margin-top: 50px;
    padding: 25px 300px;
    background: rgba(255, 255, 255, 0.26);
    border-radius: 16px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(3.9px);
    -webkit-backdrop-filter: blur(3.9px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    text-shadow: 0px 0px 13px rgba(0, 0, 0, 0.9);
}

.motto h1 {
    text-align: center;
    font-size: 2.3rem;
}

.motto p {
    text-align: center;
    font-size: 1.8rem;
}

.company {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.company h1 {
    text-align: center;
    margin-top: 30px;
    font-size: 2.3rem;
}

.company table{
    border-collapse: collapse;
    margin-top: 15px;
}

.company th, .company td {
    border: 2px solid white;
    padding: 10px;
}
</style>