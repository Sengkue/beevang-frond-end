<template>
  <div class="mt-3">
    <div class="ml-1 mb-7 font-weight-bold">ລາຍງານ</div>
    <v-row>
      <v-col cols="12" md="3" sm="12">
        <v-card
          rounded="lg"
          style="cursor: pointer"
          class="pa-3"
          to="/reports/reportProductEnd"
        >
          <div class="d-flex justify-space-around align-center">
            <v-card-subtitle>ລາຍງານສິນຄ້າໃກ້ໝົດສະຕ໊ອກ</v-card-subtitle>
            <v-btn fab small color="success">
              <v-icon>mdi-shopping</v-icon>
            </v-btn>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" md="3" sm="12">
        <v-card
          rounded="lg"
          style="cursor: pointer"
          class="pa-3"
          to="/reports/reportCustomer"
        >
          <div class="d-flex justify-space-around align-center">
            <v-card-subtitle>ລາຍງານຂໍ້ມູນລູກຄ້າ</v-card-subtitle>
            <v-btn fab small color="success">
              <v-icon color="white">mdi-account-group-outline</v-icon>
            </v-btn>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" md="3" sm="12">
        <v-card
          rounded="lg"
          style="cursor: pointer"
          class="pa-3"
          to="/reports/reportEmployee"
        >
          <div class="d-flex justify-space-around align-center">
            <v-card-subtitle>ລາຍງານຂໍ້ມູນພະນັກງານ</v-card-subtitle>
            <v-btn fab small color="success">
              <v-icon color="white">mdi-account-outline</v-icon>
            </v-btn>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" md="3" sm="12">
        <v-card
          rounded="lg"
          style="cursor: pointer"
          class="pa-3"
          to="/reports/reportTopsell"
        >
          <div class="d-flex justify-space-around align-center">
            <v-card-subtitle>ລາຍງາຍຂໍ້ມູນສິນຄ້າທີ່ຂາຍໄດ້ຫຼາຍ</v-card-subtitle>
            <v-btn fab small color="success">
              <v-icon color="white">mdi-cart-percent</v-icon>
            </v-btn>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" md="3" sm="12">
        <v-card
          rounded="lg"
          style="cursor: pointer"
          class="pa-3"
          to="/reports/reportAllProduct"
        >
          <div class="d-flex justify-space-around align-center">
            <v-card-subtitle>ລາຍງານສິນຄ້າທັງໜົດໃນສະຕ້ອກ</v-card-subtitle>
            <v-btn fab small color="success">
              <v-icon color="white">mdi-package-variant-plus</v-icon>
            </v-btn>
          </div>
        </v-card>
      </v-col>
      <v-col cols="12" md="3" sm="12">
        <v-card
          rounded="lg"
          style="cursor: pointer"
          class="pa-3"
          to="/reports/reportIncomeOutcome"
        >
          <div class="d-flex justify-space-around align-center">
            <v-card-subtitle>ລາຍງານລາຍຮັບ-ລາຍຈ່າຍ</v-card-subtitle>
            <v-btn fab small color="success">
              <v-icon color="white">mdi-currency-usd</v-icon>
            </v-btn>
          </div>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>
  
  <script>
export default {
  name: 'ReportPages',

  data() {
    return {
      showDialog: false,
      show: false,
      value: '',
      headers: [],
      items: [],
      item: [
        'ລາຍງານສະຫຼຸບລາຍຮັບ',
        'ລາຍງານຂໍ້ມູນຢາ-ອຸປະກອນ',
        'ລາຍງານຂໍ້ມູນຄົນເຈັບ',
        'ລາຍງານຂໍ້ມູນການປີ່ນປົວ',
      ],
    }
  },

  mounted() {},
}
</script>
  
  <style lang="scss" scoped></style>