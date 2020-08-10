<template>
<div>
  <main class="page-content">
    <div class="container-fluid">
      <h2> <i class="fa fa-envelope"></i> Outbox</h2>
      <hr>
      <div class="row">
        <div class="form-group col-md-12">
          <div class="row">
              <div class="col-md-10">
                  <div class="input-group">
                  <input class="form-control" type="text" name="" id="" placeholder="Pencarian..">
                    <div class="input-group-prepend">
                        <div class="input-group-text"><i class="fa fa-search"></i></div>
                    </div>
                  </div>
              </div>
              <div class="col-md-2">
                  <select class="form-control" aria-placeholder="Filter: Threads By">
                      <option>Tanggal</option>
                      <option>Nama</option>
                      <option>Jenis</option>
                  </select>
              </div>
          </div>
        </div>
      </div>
      <hr>
      <div class="col-md-12">
        <div class="row">
            <table class="table table-striped col-md-12">
                <thead class="bg-primary" style="color:white;text-align:center">
                    <tr>
                        <th colspan="2"></th>
                        <th>Dari</th>
                        <th>Tujuan</th>
                        <th>Perihal</th>
                        <th>Kategori</th>
                        <th>Tanggal</th>
                    </tr>
                </thead>
                <tbody style="text-align:left">
                    <tr>
                        <td><i class="fa fa-archive"></i></td>
                        <td><i class="fa fa-file-archive"></i></td>
                        <td>BKD Sleman</td>
                        <td>Anita Ratu</td>
                        <td>Pemberitahuan Pensiun</td>
                        <td>Pemberhentian kepada saudara..</td>
                        <td>24/05/2016</td>
                    </tr>
                    <tr>
                        <td><i class="fa fa-archive"></i></td>
                        <td><i class="fa fa-file-archive"></i></td>
                        <td>DIKPORA DIY</td>
                        <td>Anita Ratu</td>
                        <td>Undangan Rapat Dikpora</td>
                        <td>Surat Undangan</td>
                        <td>17/05/2016</td>
                    </tr>
                    <tr>
                        <td><i class="fa fa-archive"></i></td>
                        <td><i class="fa fa-file-archive"></i></td>
                        <td>KPPT Sleman</td>
                        <td>Anita Ratu</td>
                        <td>Penagihan Retribusi IMB</td>
                        <td>Pembendaharaan..</td>
                        <td>16/05/2016</td>
                    </tr>
                    <tr>
                        <td><i class="fa fa-archive"></i></td>
                        <td><i class="fa fa-file-archive"></i></td>
                        <td>SETDA Sleman</td>
                        <td>Anita Ratu</td>
                        <td>Kenaikan Gaji Berkala An. Banar Tri Koratmo</td>
                        <td>Mutas atau Kenaikan Gaji..</td>
                        <td>24/05/2016</td>
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
  name: 'Outbox'
}
</script>
