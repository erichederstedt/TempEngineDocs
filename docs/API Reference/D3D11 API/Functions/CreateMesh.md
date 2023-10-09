# CreateMesh

```c++
extern int CreateMesh(Mesh* mesh, Vertex* vertexArray, int vertexCount, int* indexArray, int indexCount);
```

Creates a mesh.


### Usage
```c++
D3DAPI::Mesh mesh;

Vertex vert_array[4] = {};
vert_array[0].pos = { -1.0f, -1.0f };
vert_array[0].uv = { 0.0f, 1.0f };
vert_array[1].pos = { -1.0f, 1.0f };
vert_array[1].uv = { 0.0f, 0.0f };
vert_array[2].pos = { 1.0f, 1.0f };
vert_array[2].uv = { 1.0f, 0.0f };
vert_array[3].pos = { 1.0f, -1.0f };
vert_array[3].uv = { 1.0f, 1.0f };
int vert_count = 4;

int index_array[6] =
{
    0, 1, 2,
    0, 2, 3
};
int index_count = 6;

if (CreateMesh(&mesh, vert_array, vert_count, index_array, index_count))
{
	// Failed
	return 1;
}
```