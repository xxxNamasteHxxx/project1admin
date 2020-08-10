<template>
<div>
  <main class="page-content">
    <div class="container-fluid">
      <h2><i class="fa fa-cog"></i><b> Pengaturan</b> / <i class="fa fa-user"></i> Profil </h2>
        <hr>
        <div class="form-group col-md-12">
            <div class="row">
                <div class="col-md-6">
                    <div class="form-group row">
                        <button class="btn btn-primary">Edit Profil</button>
                        <button class="btn btn-secondary">Excel</button>
                    </div>
                    <hr>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="form-group col-md-12">
                <div class="row alert alert-success" role="alert">
                    <div class="col-md-1">
                        <img src="../assets/icon profile.png" class="rounded-circle " width="50px">
                    </div>
                    <div class="col-md-2">
                        <p>Silviana</p>
                        <p>phie_313@yahoo.com</p>
                    </div>
                </div>
            </div>
        </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="col-sm-2 col-form-label col-form-label-sm">Nama</label>
                      <div class="col-sm-10">
                          <input type="email" class="form-control form-control-sm" placeholder="Nama..">
                      </div>
                  </div>
              </div>
          </div>
      </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="col-sm-2 col-form-label col-form-label-sm">Email</label>
                      <div class="col-sm-10">
                          <input type="email" class="form-control form-control-sm" placeholder="Email..">
                      </div>
                  </div>
              </div>
          </div>
      </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="col-sm-2 col-form-label col-form-label-sm">Gelar</label>
                      <div class="col-sm-10">
                          <input type="email" class="form-control form-control-sm" placeholder="Gelar..">
                      </div>
                  </div>
              </div>
          </div>
      </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="col-sm-2 col-form-label col-form-label-sm">NIP</label>
                      <div class="col-sm-10">
                          <input type="email" class="form-control form-control-sm" placeholder="NIP..">
                      </div>
                  </div>
              </div>
          </div>
      </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="col-md-2 col-form-label col-form-label-sm">Unit Kerja</label>
                      <div class="col-md-10">
                          <input type="email" class="form-control form-control-sm" placeholder="Unit Kerja..">
                      </div>
                  </div>
              </div>
          </div>
      </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="col-sm-2 col-form-label col-form-label-sm">Jabatan</label>
                      <div class="col-sm-10">
                          <input type="email" class="form-control form-control-sm" placeholder="ketik untuk cari jenis surat">
                      </div>
                  </div>
              </div>
          </div>
      </div>
      <div class="col-md-12">
          <div class="row">
              <div class="col-md-12">
                  <div class="form-group row">
                      <label class="rounded-circle col-sm-2 col-form-label col-form-label-sm">Avatar</label>
                      <div class="col-sm-10">
                          <img src="../assets/icon profile.png" width="50px" class="col-sm-2 col-form-label col-form-label-sm">
                      </div>
                  </div>
                  <input type="file" name="" id="">
              </div>
          </div>
      </div>
      <hr>
    </div>
  </main>
</div>
</template>

<script>
export default {
  name: 'Setting'
}
</script>
