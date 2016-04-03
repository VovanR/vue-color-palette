<template>
  <div id="app">
    <Siteheader></Siteheader>

    <div class="container">
        <div class="row">
            <div class="col-md-7">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        Added

                        <span class="badge" id="palette-count">0</span>

                        <div class="palette-multiselect">
                            <div class="palette-multiselect__checkbox-wrapper checkbox">
                                <label class="palette-multiselect__label">
                                    <input class="palette-multiselect__checkbox" type="checkbox" autocomplete="off">
                                    <span class="palette-multiselect__text">Multiselect</span>
                                </label>
                            </div>
                        </div>
                    </div>

                    <div class="panel-body">
                        <div id="palette-placeholder"></div>
                    </div>
                </div>
            </div>

            <div class="col-md-5">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        New
                    </div>

                    <div class="panel-body">
                        <div id="palette-add-color-placeholder"></div>
                    </div>
                </div>

                <div class="panel panel-default">
                    <div class="panel-heading">
                        Selected

                        <span class="badge" id="palette-selected-count">0</span>
                    </div>

                    <div class="panel-body">
                        <div id="palette-selected-colors-placeholder"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <Sitefooter></Sitefooter>
  </div>
</template>

<script>
import Siteheader from './components/Siteheader'
import Hello from './components/Hello'
import Sitefooter from './components/Sitefooter'

export default {
  components: {
    Siteheader,
    Hello,
    Sitefooter
  }
}
</script>

<style>
body {
    cursor: default;
}
</style>
