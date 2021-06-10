<template>
    <div class="container register">
        <div class="incorrect hide"></div>
        <h1>Register</h1>
        <div class="col-md -4">
            <form id="registration">
                <input type="text" class="form-control" id="firstName" placeholder="First Name" required>
                <input type="text" class="form-control" id="lastName" placeholder="Last Name" required>
                <input type="password" class="form-control" id="password" placeholder="Password" required>
                <input type="password" class="form-control" id="confirm" placeholder="Confirm Password" required>
                <button type="submit" class="btn btn-primary">Register</button>
            </form>
        </div>
    </div>
</template>
<script>
    export default {
        name: "Register"
    }
</script>