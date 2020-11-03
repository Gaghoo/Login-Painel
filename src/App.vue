<template>
    <v-app>
        <v-app-bar app dark color="indigo darken-3">
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
            <v-toolbar-title>Login Page</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn text rounded class="mx-1">
                <v-icon left>mdi-home-outline</v-icon>
                <span>Home</span>
            </v-btn>
            <v-btn text rounded class="mx-1">
                <v-icon left>mdi-card-account-details-outline</v-icon>
                <span>About Us</span>
            </v-btn>
            <v-btn text rounded class="mx-1">
                <v-icon left>mdi-account-plus-outline</v-icon>
                <span>Register</span>
            </v-btn>
        </v-app-bar>
        <v-main class="indigo lighten-4 d-flex justify-center align-center">
            <div class="d-flex justify-center">
                <v-card width="500">
                    <v-card-title>Login</v-card-title>
                    <v-card-text>
                        <v-text-field
                            label="Username"
                            outlined
                            prepend-inner-icon="mdi-account-circle-outline"
                            shaped
                        ></v-text-field>
                        <v-text-field
                            label="Password"
                            outlined
                            prepend-inner-icon="mdi-lock-outline"
                            shaped
                            type="password"
                            append-icon="mdi-eye-off-outline"
                        ></v-text-field>
                    </v-card-text>
                    <v-divider/>
                    <v-card-actions>
                        <v-btn color="indigo" elevation="6" rounded class="mx-auto my-6">
                            <v-icon left>mdi-login-variant</v-icon>
                            <span>Login</span>
                        </v-btn>
                    </v-card-actions>
                </v-card>
            </div>
        </v-main>
    </v-app>
</template>

<script>

export default {
    name: 'App',

    components: {

    },

    data: () => ({
        
    }),
};
</script>
