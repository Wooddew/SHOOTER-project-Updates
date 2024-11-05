# SHOOTER-project-Updates
public class YBoundary : MonoBehaviour
public class Enemy2 : MonoBehaviour
public float moveSpeed = 3f;
// Start is called before the first frame update
® Unity Message | 0 references void StartO
// Update is called once per frame
® Unity Message | 0 references void Update)
{
// Move towards left of the screen
transform. Translate(new Vector3(-1, -1, 0) * Time.deltaTime * moveSpeed);
if (transform. position.y < -8f)
Destroy(this.game0bject);
