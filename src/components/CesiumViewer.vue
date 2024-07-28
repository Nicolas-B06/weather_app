<script>
import { Viewer } from "cesium";
import "cesium/Source/Widgets/widgets.css";

const viewer = new Viewer("app");
viewer.scene.debugShowFramesPerSecond = true;
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#cesium-container {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
}
</style>