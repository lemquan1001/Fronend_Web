<template>
    <v-footer dark padless>
      <v-card flat tile class="black white--text py-12 px-5" width="100%">
        <v-row>
          <v-col cols="12" sm="3">
            <v-card-text class="white--text pt-0">
              <h3>Giới thiệu</h3>
            </v-card-text>
            <v-card-text class="grey--text pt-0">
              Kínhasaass mắt thời trang Chasmish là thương hiệu uy tín,<br />
               chất lượng tại Việt Nam phục vụ nhu cầu mua<br /> sắm online và trực tuyến trên toàn quốc

            </v-card-text>
            <v-toolbar flat color="transparent">
              <h3>Liên hệ</h3>
            </v-toolbar>
            <v-card-text class="grey--text pt-0">
              <v-icon>mdi-map-marker</v-icon>
              34 Nguyễn Văn Trỗi, Phương Liệt, Thanh Xuân, Hà Nội.
            </v-card-text>
            <v-card-text class="grey--text pt-0">
              <v-icon>mdi-map-marker</v-icon>
               0867033918.
            </v-card-text>
            <v-card-text class="grey--text pt-0">
              <v-icon>mdi-email-outline</v-icon>
              nguyenducthan2507@gmail.com
            </v-card-text>
            <v-card-text class="grey--text"> &#169; 2021 -2022 </v-card-text>
          </v-col>
          <v-col cols="12" sm="2">
            <v-card-text class="white--text pt-0">
              <h3>Tình trạng</h3>
            </v-card-text>
            <v-card-text class="grey--text"> Tình trạng đơn hàng </v-card-text>
            <v-card-text class="grey--text mt-n4">
              Vận chuyển và giao hàng
            </v-card-text>
            <v-card-text class="grey--text mt-n4"> Khác. </v-card-text>
          </v-col>
          <v-col cols="12" sm="2">
            <v-card-text class="white--text pt-0">
              <h3>Sản phẩm</h3>
            </v-card-text>
            <v-card-text class="grey--text"> Kính nam </v-card-text>
            <v-card-text class="grey--text mt-n4"> Kính nữ </v-card-text>
            <v-card-text class="grey--text mt-n4"> Kính cận </v-card-text>
            <v-card-text class="grey--text mt-n4">
              Kính thời trang
            </v-card-text>
          </v-col>

          <v-col cols="12" sm="2">
            <v-card-text class="white--text pt-0">
              <h3>Theo dõi chúng tôi trên</h3>
            </v-card-text>
            <v-card-text class="pt-0">
              <v-btn
                v-for="icon in icons"
                :key="icon"
                class="mx-1 white--text"
                icon
              >
                <v-icon size="24px">
                  {{ icon }}
                </v-icon>
              </v-btn>
            </v-card-text>
            <v-card-text class="gwhite--text mt-14"><h3>Phương thức thanh toán:</h3> </v-card-text>
            <v-toolbar flat color="transparent">
              <!-- <v-spacer></v-spacer> -->
              <v-icon large>fab fa-cc-visa</v-icon>
              <v-icon class="mx-2" large>fab fa-cc-paypal</v-icon>
            </v-toolbar>
          </v-col>
          <v-col cols="12" sm="3">
            <v-card-text class="white--text pt-0 text-center">
              <h3>Nhận thông tin khuyến mãi</h3>
            </v-card-text>
            <h5 class="text-center grey--text">
              Đăng ký nhận bản tin của chúng tôi để nhận tin<br /> tức sự kiện mới từ chúng tôi qua địa chỉ email <br />của bạn.
            </h5>
            <v-card flat color="transparent" class="d-flex justify-center">
              <v-text-field
                placeholder="Enter Your Email"
                rounded
                class="shrink"
                background-color="grey"
                filled
                append-icon="mdi-email-outline"
                dense
              ></v-text-field>
            </v-card>
          </v-col>
        </v-row>
      </v-card>
    </v-footer>
  </template>
  
  <script>
  export default {
    data: () => ({
      icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
    }),
  };
  </script>
  
  <style>
  </style>