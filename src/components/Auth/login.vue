<template>
    <div class="container login">
        <div class="incorrect hide"></div>
        <h1>Login</h1>
        <div class="col-md -4">
            <form id="registration">
                <input type="text" class="form-control" id="username" placeholder="Username" required>
                <input type="password" class="form-control" id="password" placeholder="Password" required>
                <button type="submit" class="btn btn-primary">Login</button>
            </form>
        </div>
    </div>
</template>
<script>
    export default {
        name: "Register"
    }
</script>