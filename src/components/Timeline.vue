<template>
    <v-row class="text-center">
      <v-col md="12">
          <v-card class="mx-auto pa-4 rounded" flat>
            <v-row justify="center">
              <v-col lg="6" md="9" sm="12">
                <UserPost/>
              </v-col>
            </v-row>
          </v-card>
      </v-col>
    </v-row>
</template>

<script>
import UserPost from "@/components/UserPost";
  export default {
    name: 'Timeline',
    components: { UserPost }
  }
</script>
