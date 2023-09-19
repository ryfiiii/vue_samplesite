<template>
    <div id="contact" class="animate__animated animate__fadeIn animate__slow">
        <div class="card">
            <h1>お問い合わせ</h1>
            <form action="/">
                <table>
                    <tr>
                        <th>名前:</th>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <th>年齢:</th>
                        <td><input type="number"></td>
                    </tr>
                    <tr>
                        <th>メール:</th>
                        <td><input type="email"></td>
                    </tr>
                    <tr>
                        <th>内容:</th>
                        <td><textarea></textarea></td>
                    </tr>
                </table>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: "Contact",
}
</script>

<style scoped>
    #contact {
        height: 100vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
    .card {
        margin-top: 50px;
        padding: 25px 200px;
        background: rgba(255, 255, 255, 0.26);
        border-radius: 16px;
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        backdrop-filter: blur(3.9px);
        -webkit-backdrop-filter: blur(3.9px);
        border: 1px solid rgba(255, 255, 255, 0.3);
        text-shadow: 0px 0px 13px rgba(0, 0, 0, 0.9);
    }
    h1 {
        text-align: center;
        font-size: 2.3rem;
    }
    table {
        margin-top: 25px;
    }
    th{
        font-size: 1.2rem;
    }
    th,td {
        padding: 10px;
    }
    input {
        color: black;
        padding: 10px 20px;
        border-radius: 8px;
        outline: none;
        border: 3px solid rgb(136, 186, 255);
    }
    input:focus {
        border: 3px solid rgb(0, 92, 222);
    }
    textarea {
        color: black;
        padding: 30px 75px;
        border-radius: 8px;
        outline: none;
        border: 3px solid rgb(136, 186, 255);
    }
    textarea:focus {
        border: 3px solid rgb(0, 92, 222);
    }

@media(max-width: 768px){
    .card {
        padding: 25px 10px;
    }    
    h1 {
        font-size: 1.5rem;
    }
    th{
        font-size: 1.1rem;
    }
    input {
        color: black;
        padding: 10px 20px;
        border-radius: 8px;
        outline: none;
        border: 3px solid rgb(136, 186, 255);
    }
    input:focus {
        border: 3px solid rgb(0, 92, 222);
    }
    textarea {
        color: black;
        padding: 40px 30px;
        border-radius: 8px;
        outline: none;
        border: 3px solid rgb(136, 186, 255);
    }
}
</style>