How to Use:

Put the SceneManager File onto a GameObject and reference a loading Screen

SceneManager.Instance.LoadScene(sceneToLoadIndex, activeSceneIndex);
SceneManager.Instance.UnLoadScene(sceneToUnLoadIndex, activeSceneIndex);

Code example:
SceneManager.Instance.LoadScene((int)SceneIndexes.NetworkLayer, (int)SceneIndexes.NetworkLayer);
