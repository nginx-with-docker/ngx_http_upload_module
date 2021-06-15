# ngx_http_upload_module

A module for nginx web server for handling file uploads using multipart/form-data encoding (RFC 1867).

- Official: https://github.com/fdintino/nginx-upload-module
- Build: https://github.com/nginx-with-docker/nginx-upload-module-src
## Nginx Images

<table>
    <thead>
        <tr>
            <th>Nginx Version</th>
            <th>Module Version</th>
            <th>Docker Images</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.21.0</td>
            <td>master (2020)</td>
            <td><ul>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-upload-master</li>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-upload-master-alpine</li>
            </ul></td>
        </tr>
        <tr>
            <td>1.21.0</td>
            <td>2.3.0 (2018)</td>
            <td><ul>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-upload-2.3.0</li>
                <li>docker pull soulteary/prebuilt-nginx-modules:ngx-1.21.0-upload-2.3.0-alpine</li>
            </ul></td>
        </tr>
    </tbody>
</table>

## TODO

- try merge changes: https://github.com/fdintino/nginx-upload-module/pull/114
