<div class="authContainer">
    <form>
        <h1>Login</h1>
        <label for="">
            <input type="email" placeholder="Email">
        </label>
        <label for="">
            <input type="password" placeholder="Password">
        </label>
        <label for="">
            <input type="password" placeholder="Confirm Password">
        </label>
        <button type="submit" class="btn btn-primary">Submit</button>
    </form>
</div>
<style>
    .authContainer{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        flex: 1;
    }
    form{
        display: flex;
        flex-direction: column;
        gap: 14px;
        width: 400px;
        max-width: 100%;
        margin:  0 auto;
    }
    form input {
        width: 100%;
        border: none;
        background: transparent;
        color: white;
    }
    h1 {
        text-align: center;
        font-size: 3rem;
        
    }
    form input {
 
        border: none;
        background: transparent;
        color: white;
        padding:  14px;
        font-size: 14px;
    }
    form input:focus {
       border:none;
       outline: none;
       }
       form label {
        position: relative;
        border: 1px solid blue;
        border-radius: 5px;
       }
       form button {
        background-color: navy;
        color: white;
        outline: none;
        border: none;
        padding: 10px;
        text-transform: uppercase;
        border-radius: 5px;
        cursor: pointer;
        transition: ease-in-out;
        font-size: 1.2rem;
       }
       form button:hover {
        transition: ease-in-out;
        background-color: blue;
       }
</style>