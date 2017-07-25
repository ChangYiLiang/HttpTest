# HttpTest
模拟Http请求
包含
  sendGet(String url);
  sendPost(String url, Map<String, String> map);
  sendPost(String url, File file);
  sendPost(String url, String jsonStr);
四个接口.
添加"User-Agent"请求头，防止请求被当成攻击.
