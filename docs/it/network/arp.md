# 【ARPとは】主な機能

## ARPとは

ARP(Address Resolution Protocol)とは、IPアドレスからMACアドレスを取得するデータリンク層のプロトコルです。
データリンク層のプロトコルなのでつまりルータを超えた(異なるネットワークセグメント)にある端末からはMACアドレスを取得できません。

## ARPのフロー

● 自身のARPテーブルに、指定されたIPアドレスに対応するMACアドレスが記録されているか確認。

● 記録されていた場合、そのMACアドレスを利用。記録されていない場合、ARP要求をブロードキャストし、指定のIPアドレスを保持しているホストに返答を求める。

● ARP要求で指定されたIPアドレスを保持しているホストは、ARP要求の送信元にARP応答をユニキャストで送信。

● ARP要求の送信元は、ARP応答の送信元MACアドレスを参照し、指定したIPアドレスに対応するMACアドレスを取得。
同時に自身のARPテーブルに、そのMACアドレスとIPアドレスの組み合わせを記録し、一定時間保存する。

