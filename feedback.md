you have 2 errors :
1 --> auto is not a valid value for padding property, the only thing you can do is take out padding: 0; from the \* declaration, else simply assign padding to respective property block.

If you remove padding: 0; from _ {} than browser will apply default styles to your elements which will give you unexpected cross browser positioning offsets by few pixels, so it is better to assign padding: 0; using _ and than if you want to override the padding, simply use another rule like

.container p {
padding: 5px;
}

2 ----> when you use rgba function plz donot forget the ().
3 ----> In general you did a lot of effort and the good point is you will be a super powerful developer
