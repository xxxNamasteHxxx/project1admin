<template>
<div>
  <main class="page-content">
    <div class="container-fluid">
      <h2><b>Laporan</b> / Surat Keluar </h2>
      <hr>
        <div class="row">
            <div class="form-group col-md-12">
                <div class="row">
                    <div class="col-md-5">
                    <div class="form-group row">
                        <label class="col-sm-2 col-form-label col-form-label-sm">Periode</label>
                        <div class="col-sm-10">
                        <input type="email" class="form-control form-control-sm" placeholder="01/05/2016">
                    </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                    <div class="form-group row">
                        <label class="col-sm-2 col-form-label col-form-label-sm">s.d.</label>
                        <div class="col-sm-10">
                        <input type="email" class="form-control form-control-sm" placeholder="31/05/2016">
                        </div>
                    </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="form-group col-md-12">
            <div class="row">
                <div class="col-md-6">
                    <div class="form-group row">
                        <button class="btn">Cari</button>
                        <button class="btn">Tampilkan Filter Lanjutan</button>
                    </div>
                </div>
            </div>
        </div>
        <hr>
        <div class="form-group col-md-12">
            <div class="row">
                <div class="col-md-6">
                    <div class="form-group row">
                        <button class="btn"> <i class="fa fa-print"></i> Cetak</button>
                        <button class="btn"> <i class="fa fa-file-excel"></i> Excel</button>
                    </div>
                </div>
            </div>
        </div>
      <div class="col-md-12">
        <div class="row">
            <table class="table table-striped col-md-12">
                <thead class="bg-primary" style="color:white;text-align:center">
                    <tr>
                        <th>No</th>
                        <th>Tanggal</th>
                        <th>Nomor</th>
                        <th>Dari</th>
                        <th>Perihal</th>
                        <th>Pelaksana Teknis</th>
                    </tr>
                </thead>
                <tbody style="text-align:left">
                    <tr>
                        <td>1</td>
                        <td>24/05/2016</td>
                        <td>882/2016</td>
                        <td>BKD Sleman</td>
                        <td>Pemberitahuan Pensiun</td>
                        <td>Anita Ratu</td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>24/05/2016</td>
                        <td>882/2016</td>
                        <td>BKD Sleman</td>
                        <td>Pemberitahuan Pensiun</td>
                        <td>Anita Ratu</td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>24/05/2016</td>
                        <td>882/2016</td>
                        <td>BKD Sleman</td>
                        <td>Pemberitahuan Pensiun</td>
                        <td>Anita Ratu</td>
                    </tr>
                </tbody>
            </table>
        </div>
      </div>
      <hr>
    </div>
  </main>
</div>
</template>

<script>
export default {
  name: 'Laporansuratkeluar'
}
</script>
