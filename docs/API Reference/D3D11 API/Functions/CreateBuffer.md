# CreateBuffer

```c++
extern int CreateBuffer(ID3D11Buffer** buffer, D3D11_BIND_FLAG bindFlag, void* data, int dataSize);
```

Simpel abstraction for creating buffers that are used by the GPU. Used for creating vertex and index buffers etc.


### Usage
```c++
ID3D11Buffer* vertexBuffer = NULL;

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

if (D3DAPI::CreateBuffer(&vertexBuffer, D3D11_BIND_VERTEX_BUFFER, vertex_array, sizeof(Vertex) * vertex_count))
{
	// Failed
	return 1;
}
```