<template>
  <div id="app">
    <div style="width: 100%; height: 50px;position: fixed; left: 0;top: 0;background: red;z-index: 10;"></div>
    <Row :gutter="32">
      <Col span="16">
        <Card>
          <div style="height: 600px;">1111</div>
        </Card>
      </Col>
      <Col span="8">
        <Card>
          <div style="height: 200px;">2222</div>
        </Card>
        <Affix :offset-top="50">
          <Card>
            <div style="height: 200px;">2222</div>
          </Card>
        </Affix>
      </Col>
    </Row>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style>
  body {
    height: 5000px;
    background: #808695 !important;
  }
</style>

