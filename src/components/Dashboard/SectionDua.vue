<template>
  <section class="sec2 container p-5">
    <div class="row text-center text-white p-5">
      <h1>Verifikasi Halal Blockchain</h1>
      <p>Verifikasi Ke-Halalan Blockchain kamu dengan masukkan code atau upload barcode atau QR kamu!</p>
    </div>
    <div class="card p-3">
      <form>
        <div class="form-group">
          <label for="exampleInputEmail1">Masukkan Kode</label>
          <div class="row">
            <div class="col-11">
              <input type="text" id="inputPassword6" class="form-control" aria-describedby="passwordHelpInline" />
            </div>
            <div class="col-1">
              <button type="submit" class="btn btn-warning">Submit</button>
            </div>
          </div>
        </div>
        <div class="form-group pt-2">
          <label for="exampleInputPassword1">Atau Upload Barcode / QR</label>
          <div class="input-group">
            <input type="file" class="form-control" id="inputGroupFile02" />
            <label class="input-group-text" for="inputGroupFile02">Upload</label>
          </div>
        </div>
        <div class="form-group pt-2">
          <label for="exampleInputPassword1">Hasil Verifikasi</label>
          <div class="d-grid gap-2">
            <button class="btn btn-warning" type="button">Lihat</button>
          </div>
        </div>
      </form>
    </div>
  </section>
</template>

<style scoped>
.sec2.container {
  padding: 0;
  background-color: #239f9f;
  box-sizing: border-box;
  height: auto;
  /* min-height: 100vh; */
  overflow: hidden;
  /* padding: 80px 100px 150px; */
  position: relative;
  width: 100%;
  /* margin: 0; */
}
</style>
